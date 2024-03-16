# Ukulele-tuner
This piece of Python code is a console application that you can use to tune your Ukulele for my school DSP final project. It is fully functional, complete with a TUII and easily extensible to other stringed instruments.

## Installation
First install dependencies and library pyaudio. On windows, you can download the binary and install it. On linux, you can run `pip install pyaudio`.

Next, you will need numpy. Install it with `pip install numpy`. 

This done, you are ready to run the tool.

## Usage
The interface is text print out in the terminal and looks like this,

+----------------------------------------------------------+
|                          TUNERR                          |
+----------------------------------------------------------+
| C   C#    D   D#    E    F   F#    G   G#    A   A#    B |
+------------------------------------^---------------------+
|  -0.5 -0.4 -0.3 -0.2 -0.1   0  +0.1 +0.2 +0.3 +0.4 +0.5  |
+---------------------------------------------------^------+
|  FREQ:  402.40 Hz                       NOTE: G.4.583333333333333 +0.45  |
+----------------------------------------------------------+
 
The first line tells user name of the notes.

| C   C#    D   D#    E    F   F#    G   G#    A   A#    B |
    
The next line is the central values.

|  -0.5 -0.4 -0.3 -0.2 -0.1   0  +0.1 +0.2 +0.3 +0.4 +0.5  |

The last line tell user the frequency and name of the note.

|  FREQ:  402.40 Hz                       NOTE: G.4.583333333333333 +0.45  |

These two are spectial line that moving constantly due to the input frequency it take from the user.

+-----------------------------^---------------------------+

NOTE: Enjoy this fun tool. Feel free to use my project as reference or improve it to a flly bulid functional application.

sign: iamno
