# xavs
git mirror of the xavs svn repository

 

1. Download the xavs sourcecode: 
   `git clone https://github.com/pandastream/xavs.git`

2. Compile the xavs code
    Install your xavs and Prefix the .h file and the .a  file into the system directory like /usr/local. 

   ```bash
    ./configure --prefix="$HOME/ffmpeg_build" --bindir="$HOME/bin" --enable-shared 
    make 
    make install
   ```

   


### Refer

[Linux中安装FFmpeg详解](https://www.linuxidc.com/Linux/2019-03/157443.htm)

[Welcome to the XAVS Home!](http://xavs.sourceforge.net/)

[xavs source code - code](http://svn.code.sf.net/p/xavs/code/trunk/)

[How to trancode other video formats to AVS using ffmpeg under Linux](http://xavs.sourceforge.net/xavs_ffmpeg.html)

