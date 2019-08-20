#  How to convert text to PDF in Linux #

# for CentOS/RedHat
yum install enscript a2ps ghostscript -y

# for Ubuntu
sudo apt install enscript a2ps ghostscript -y

# How to Convert

enscript -p output.ps imtextfile.txt

ps2pdf output.ps imtextfile.pdf

# Link to website :- https://the-d2.com/how-to-convert-text-to-pdf-in-linux/
