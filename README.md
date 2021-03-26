# tens
Tens Scripts
TENS:~$ history 
   0 history 
TENS:~$ xrandr --verbose
xrandr: Failed to get size of gamma for output default
Screen 0: minimum 1280 x 800, current 1280 x 800, maximum 1280 x 800
default connected 1280x800+0+0 (0x399) normal (normal) 0mm x 0mm
	Identifier: 0x398
	Timestamp:  1571072
	Subpixel:   unknown
	Clones:    
	CRTC:       0
	CRTCs:      0
	Transform:  1.000000 0.000000 0.000000
	            0.000000 1.000000 0.000000
	            0.000000 0.000000 1.000000
	           filter: 
	non-desktop: 0 
		supported: 0, 1
  1280x800 (0x399) 61.440MHz *current
        h: width  1280 start    0 end    0 total 1280 skew    0 clock  48.00KHz
        v: height  800 start    0 end    0 total  800           clock  60.00Hz
TENS:~$ Modegit
bash: Modegit: not found
TENS:~$ git
bash: git: not found
TENS:~$ vi xrandr.sh
TENS:~$ Modeline "1280x800_60" 61.440 1280 0 0 1280 800 0 0 800 +HSync -Vsync
bash: Modeline: not found
1abb987ccd2b84:~$ xrandr -d :0 --newmode "1280x800_60" 61.440 1280 0 0 1280 800 
0 0 800 +HSync -Vsync
xrandr: Failed to get size of gamma for output default
1abb987ccd2b84:~$ xrandr --output default --gamma 0:0:0 -mode 1280x800
xrandr: gamma correction factors must be positive
Try 'xrandr --help' for more information.
1abb987ccd2b84:~$ xrandr --output default --gamma 0:0:0 --mode 1280x800
xrandr: gamma correction factors must be positive
Try 'xrandr --help' for more information.
1abb987ccd2b84:~$ xrandr --output default --gamma 1:1:1 --mode 1280x800
xrandr: Gamma size is 0.
1abb987ccd2b84:~$ xrandr --verbose
xrandr: Failed to get size of gamma for output default
Screen 0: minimum 1280 x 800, current 1280 x 800, maximum 1280 x 800
default connected 1280x800+0+0 (0x399) normal (normal) 0mm x 0mm
	Identifier: 0x398
	Timestamp:  1571072
	Subpixel:   unknown
	Clones:    
	CRTC:       0
	CRTCs:      0
	Transform:  1.000000 0.000000 0.000000
	            0.000000 1.000000 0.000000
	            0.000000 0.000000 1.000000
	           filter: 
	non-desktop: 0 
		supported: 0, 1
  1280x800 (0x399) 61.440MHz *current
        h: width  1280 start    0 end    0 total 1280 skew    0 clock  48.00KHz
        v: height  800 start    0 end    0 total  800           clock  60.00Hz
  1280x800_60 (0x3b3) 61.440MHz +HSync -VSync
        h: width  1280 start    0 end    0 total 1280 skew    0 clock  48.00KHz
        v: height  800 start    0 end    0 total  800           clock  60.00Hz
1abb987ccd2b84:~$ xrandr --output default --gamma 1:1:1 --mode 1280x800
xrandr: Gamma size is 0.
1abb987ccd2b84:~$ xrandr --verbose
xrandr: Failed to get size of gamma for output default
Screen 0: minimum 1280 x 800, current 1280 x 800, maximum 1280 x 800
default connected 1280x800+0+0 (0x399) normal (normal) 0mm x 0mm
	Identifier: 0x398
	Timestamp:  1571072
	Subpixel:   unknown
	Clones:    
	CRTC:       0
	CRTCs:      0
	Transform:  1.000000 0.000000 0.000000
	            0.000000 1.000000 0.000000
	            0.000000 0.000000 1.000000
	           filter: 
	non-desktop: 0 
		supported: 0, 1
  1280x800 (0x399) 61.440MHz *current
        h: width  1280 start    0 end    0 total 1280 skew    0 clock  48.00KHz
        v: height  800 start    0 end    0 total  800           clock  60.00Hz
  1280x800_60 (0x3b3) 61.440MHz +HSync -VSync
        h: width  1280 start    0 end    0 total 1280 skew    0 clock  48.00KHz
        v: height  800 start    0 end    0 total  800           clock  60.00Hz
1abb987ccd2b84:~$ xrandr --addmode default 1280x800_60
xrandr: Failed to get size of gamma for output default
1abb987ccd2b84:~$ xrandr --game 1:1:1 --addmode default 1280x800_60
xrandr: unrecognized option '--game'
Try 'xrandr --help' for more information.
1abb987ccd2b84:~$ xrandr --gamma 1:1:1 --addmode default 1280x800_60
xrandr: --gamma must be used after --output
Try 'xrandr --help' for more information.
1abb987ccd2b84:~$ xrandr --addmode default 1280x800_60
xrandr: Failed to get size of gamma for output default
