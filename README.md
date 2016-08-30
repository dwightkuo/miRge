Official documentation for miRge can be found at our main website: 

http://atlas.pathology.jhu.edu/baras/miRge.html

# Installation

## Obtaining miRge:

miRge may be cloned from this repository by the following command:

`git clone https://github.com/BarasLab/miRge.git`

## System/Perl/Python Dependencies:

All required libraries may be installed on a ubuntu variant with this command:

`sudo apt-get update`

`sudo apt-get install libgd-graph-perl libhtml-table-perl python-setuptools python-dev unzip`

### Cutadapt:

`pip install cutadapt==1.8.1 or easy_install cutadapt==1.8.1`

OR if you lack root privs

`pip install --user cutadapt==1.8.1 or easy_install --user cutadapt==1.8.1`

Note: if you install it as a non-root user, you must ensure the install location is on your path, or specify the location of cutadapt with the --cutadapt argument. This is usually in ~/.local/bin/cutadapt, but may vary with your particular distribution. **At this time, miRge has been tested with cutadapt versions 1.8.1 and 1.9.x, and is not compatible at this time with cutadapt 1.10.x.**

### Bowtie:

This version may not be the latest, visit the official Bowtie website for the latest version

`wget http://sourceforge.net/projects/bowtie-bio/files/bowtie/1.1.1/bowtie-1.1.1-linux-x86_64.zip/download`

It may be saved as 'download' or 'bowtie-xxx', so run 'unzip download.zip' to extract it to a given location

### Sequence Libraries:

From within the directory miRge is installed in, run:

`wget http://atlas.pathology.jhu.edu/baras/miRge/miRge.seqLibs.tar.gz`

`tar -zxvf miRge.seqLibs.tar.gz`

## User Manual

http://atlas.pathology.jhu.edu/baras/miRge/miRge_help.html
