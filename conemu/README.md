# Ayume - ConEmu

ConEmu is a tabbed terminal emulator for Windows with a variety of improvements and features over the typical Windows terminal.

## Install Instructions

1. Navigate to `~/AppData/Roaming/` and open `ConEmu.xml` in a text editor.
2. Scroll down to where `<key name="Colors"` begins.
3. Replace `<key name="Palette1" ...>` with the contents from [ayume.xml](https://raw.githubusercontent.com/kvnxiao/ayume/master/conemu/ayume.xml).
4. To match the status bar icon colours, find and replace the following lines in `ConEmu.xml` with:
```xml
			<value name="StatusBar.Color.Back" type="dword" data="00332721"/>
			<value name="StatusBar.Color.Light" type="dword" data="00c3ced0"/>
			<value name="StatusBar.Color.Dark" type="dword" data="00877360"/>
```