## Day 02 "The Coder's Computer" 

**THE MOST POPULAR TEXT EDITORS FOR CODING:**
- NotePad++ (Windows only);
- TextWrangler/BB Edit (Mac only);
- Visual Studio Code (Microsoft, Cross-platform);
- Atom (GitHub, Cross-platform);
- Brackets (Adobe, Cross-platform);
- Sublime Text (Cross-platform);

**COMMAND LINE/TERMINAL/SHELL**

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.
The command line typically presents you with a prompt. Then you can enter a command (ls, pwd, cd etc). The command can be followed by arguments separated by spaces (eg -l /home/ryan ). The first command line argument ( -l ) is also referred to as an option. Options are typically used to modify the behaviour of the command. Options are usually listed before other arguments and typically start with a dash ( - ). 
Linux is case sensitive!

**COMMAND LIST:**
- **_pwd_** (Print Working Directory) - tells you whar directorey you're at;
- **_ls_** (List) - lists what is in the current location;
     **OPTIONS:**
    - **_-l_** - long listing
    ![ls -l example](https://lh3.googleusercontent.com/_4bL8WTjZS-AqdSAq0x2_eidN5oxmewQMzxOsefbdQmycObOC316nMb1G8ktz31AAz8Zk6NQ2oB0DVq1jAz1_jcWH4Kf4SM6KqsNWRq79wlFj-XQ9P3i2oi1S4egwa2pC9A7mhZI8SJ_wxh6vrLBWyNKKa1v3GvVGvGB6N9Ijf1nh4T2njdN_8o4_m0tTi2ARFP5s6DcakENwqhvwkZiXvO8Jh2jC6PrjIgfv3L0lu_yyD7BXV0UbUuN2bmt1heYgDbKRUrLyre2GLOm_RG1yfRvXAWmQuESUFAYZ2vyQOsT_RUyvc9kQnI_2Bfu7T2rPieuvf7lOncbYSZg98uiMmgnUzrAmqnxsMkZg4Ed9qMv3Xf6ll2icKwXax_0RqAaUSAKvD1_0DEv8PDvqz1FXILg3mkrKRxLGB-2GoaUJfr_xJhfpyHem5oyR4qyo5pFJ4f3ms_FT1uP3sAASjYrzsJuGL1GljB7A6Xdp3bNW8oeDJO1zoXO77ibBfnATobN_Thq7WUg87PogxtI733oi317wuDiC-MsXxE8IdOjEFDB2SX6APbN9aqgPR8ju8rt8oedvWqaws7bBh_9ZDXmhoSVkNyJWvVLB0cqfY8s8qL4282fcUS2S6eD5wqgT0Aj7HEiDzr1_ebCvXWw-bJ6dpwFGLFWP9K_6_2Osbjvv03HaGXlrdbRwKgD00F2tP6GRa7uUYVLuFX_aBELPXNzRLhhVA=w1167-h261-no)
    1 - d (directory), - (file);
    2 - permissions;
    3 - block numbers;
    4 - directory owner;
    5 - group;
    6 - directory/file size;
    7 - last edited;
    8 - directory/file name.
    - **_/etc_** - lists not the curren directory but instead that directories contents;
    - **_-a_** - lists hidden files;
    - you can also combine them (_ls -l /etc_ - will show long listing of directories contents).
- **_cd_** (Change Directory) - changes your current location (*cd Documents*, *cd ~/Documents*, *cd /*);
    - **_cd $wr_** - brings to Windows FS root foldel;
    - **_cdwr_** - in our particular */.profile* (this file stores terminal's profile settings) brings to Windows FS root;
    - **_cd ~_** - brings to Linux FS root;
    - **_cd /mnt_** - go to drives list;
- **_code_** - open VS Code (or whatever text editor you set it up for);
    - **_code ._** - open all files in current directory in VS Code;
- **_clear_** - clear terminal window;
- **_man_** - open manual (for example *man tree*);
- **_mkdir_** - create new folder;
- `sudo apt-get upgrade` - get updates;
- **_file_** - obtains information about what type of file a file or directory is.

**PATHS: ABSOLUTE AND RELATIVE**

The very top of Linux hierarchical structure is /ROOT (/).
- **_~(tilde)_** - home directory (~/Documents = home/ryan/Documents);
- **_.(dot)_** - current directory (./Documents = Documents);
- **_..(dotdot)_** - parent directory (../../ will bring you 2 directories above the one you're in).

If you need to use path that contains spaces use quotes ' or " (cd 'Holiday Photos') or escape character (cd Holiday\ Photos). 
Hidden files or directories start with **"."**(full stop). For example: .file.txt

Here you can find [computer setup guide](http://codefellows.github.io/code-201-prework/prework/).

[Go back to page 1](readme.md)