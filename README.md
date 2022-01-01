# Manual Align
A tool that can help you manually align text to audio, adjust existing alignments, edit transcripts, etc. in your process of creating a speech dataset.

## Install
Get the code, and open it with any modern browser.

## Usage
### Loading files
To begin, load an audio file and a TXT or JSON file.

If you use TXT, split your text into lines.  
For a JSON file, it should be like the following:
```json
[{"Start": Starting time of this line in millisecond, 
"Stop": Ending time of this line in millisecond, 
"Text":The text of this line},
...]
```

After loading, play the audio for a few seconds so that the regions on the wave are placed at the correct positions.   
After editing, click ```Save``` can save your edit into a JSON in the above format.  

### Keyboard shortcuts
There are some keyboard shortcuts to help you do your work easilier.  
```ENTER```: Play/Pause the audio.  
```SPACE```: Play audio of the current line.  
```UP```: Go to previous line.  
```DOWN```: Go to next line.  
```LEFT / RIGHT```: Move the player cursor backward/forward.  
```CTRL + LEFT / RIGHT```: Skip to the previous/next region boundary.  
```F```: Set Start. ```D```: Shift Start 10ms later. ```S```: Shift Start 10ms earlier.  
```J```: Set End. ```K```: Shift End 10ms earlier. ```L```: Shift End 10ms later.  

If you need help about the keyboard shortcuts when editing, simply click the blue icon next to the title.
