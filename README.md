# Nostalgia-on-ChromeOS
An instruction manual containing Linux sudo codes that allow for PCCD-issued Chromebooks to install and play 8-bit retro games for free.



Updating Linux:

    sudo apt update
    sudo apt upgrade

Press Y to accept installation.

Installing Doom:

    sudo apt-get install chocolate-doom
    doom

That's it really. Enjoy Doom on ChromeOS.
    
Installing 'Duke Nukem 3D: Atomic Edition:

Download prerequisites.

    sudo apt-get install build-essential nasm libgl1-mesa-dev libsdl2-dev flac libflac-dev libvpx-dev libgtk2.0-dev freepats

Press Y to accept installation.

Download 'eduke32_src_20240217-10554-8afa42e38.tar.xz' from the link below.

    https://dukeworld.com/eduke32/synthesis/latest/

Download 'DUKE3D.GRP' by selecting 'Duke3d Atomic Edition/DUKE3D.GRP' from the link below.

    https://ia800902.us.archive.org/view_archive.php?archive=/13/items/Duke3dAtomicEdition/Duke3d%20Atomic%20Edition.rar

Make a directory titled 'DukeNukem' (or whatever else you want).

Copy and paste 'eduke32_src_20240217-10554-8afa42e38.tar.xz' from your computer's downloads folder and into 'DukeNukem'.

Enter the directory.

    cd DukeNukem

Unzip 'eduke32_src_20240217-10554-8afa42e38.tar.xz'.

    tar -xf eduke32_src_20240217-10554-8afa42e38.tar.xz

Enter the unzipped folder.

    cd eduke32_20240217-10554-8afa42e38

Copy and paste 'DUKE3D.GRP' from your computer's downloads folder and into 'eduke32_20240217-10554-8afa42e38'.

Compile 'DUKE3D.GRP'.

    make RELEASE=0

Run Duke Nukem 3D.
    
    ./eduke32

Enjoy 'Duke Nukem 3D: Atomic Edition' on ChromeOS.
