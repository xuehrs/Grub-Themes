[https://xuehrs.github.io/2018/05/01/grub2%E7%BE%8E%E5%8C%96/003.pnghttps://xuehrs.github.io/2018/05/01/grub2%E7%BE%8E%E5%8C%96/003.pngIntroduction-of-documents](README.md) [中文文档](README-zh.md)

# Explanation
This is the theme of a Grub2
![](https://xuehrs.github.io/2018/05/01/grub2%E7%BE%8E%E5%8C%96/003.png)
[Reference picture](https://xuehrs.github.io/2018/05/01/grub2%E7%BE%8E%E5%8C%96/003.png)
# How to install the Grub2 theme
Requirements for the environment: efi+gpt, archlinux
My partition:

![001](https://xuehrs.github.io/2018/05/01/grub2%E7%BE%8E%E5%8C%96/001.png)
![002](https://xuehrs.github.io/2018/05/01/grub2%E7%BE%8E%E5%8C%96/002.png)

copy files Griffin-Grub-v2.0 to /boot/grub/themes/ partition, there is a script, will automatically process theme theme files.
````
command:
cd /boot/grub/themes/Griffin-Grub-v2.0/
chmod +x Install-Arch.sh 	#generally negligible, can be used
sudo./Install-Arch.sh
````
No, then **reboot**, you can see.
ote: If you are **Ubuntu**, in general, please change the Install-Arch.sh above to Install-Ubuntu.sh.


# Update content
This Grub-Themes is modified based on the Shenron007/Grub-Themes source file in githun.
link: https://github.com/Shenron007/Grub-Themes/tree/griffin-grub
simply change the grub-update command to grub-mkconfig -o /boot/grub/grub.cfg.

update date: 2018-05-02 10:49:42