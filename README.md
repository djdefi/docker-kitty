# Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Quick Start](#quick-start)


# Introduction

Dockerfile to build a [kitty](https://github.com/bryanwoods/kitty) image.

# Installation

Pull the latest version of the image from the docker index. This is the recommended method of installation as it is easier to update image in the future. These builds are performed by the **Docker Trusted Build** service.

```bash
docker pull djdefi/docker-kitty:latest
```

Alternately you can build the image locally.

```bash
git clone https://github.com/rtrauntvein/docker-kitty.git
cd docker-kitty
docker build --tag="$USER/kitty" .
```

# Quick Start

Run the image

```bash
$ docker run djdefi/docker-kitty
               *     ,MMM8&&&.            *
                    MMMM88&&&&&    .
                   MMMM88&&&&&&&
       *           MMM88&&&&&&&&
                   MMM88&&&&&&&&
                   'MMM88&&&&&&'
                     'MMM8&&&'      *
            |\___/|
            )     (             .              '
           =\     /=
             )===(       *
            /     \
            |     |
           /       \
           \       /
    _/\_/\_/\__  _/_/\_/\_/\_/\_/\_/\_/\_/\_/\_
    |  |  |  |( (  |  |  |  |  |  |  |  |  |  |
    |  |  |  | ) ) |  |  |  |  |  |  |  |  |  |
    |  |  |  |(_(  |  |  |  |  |  |  |  |  |  |
    |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
    |  |  |  |  |  |  |  |  |  |  |  |  |  |  |

# More than one kitty:
$ docker run djdefi/docker-kitty 5
               *     ,MMM8&&&.            *
                    MMMM88&&&&&    .
                   MMMM88&&&&&&&
       *           MMM88&&&&&&&&
                   MMM88&&&&&&&&
                   'MMM88&&&&&&'
                     'MMM8&&&'      *
            |\___/|
            )     (             .              '
           =\     /=
             )===(       *
            /     \
            |     |
           /       \
           \       /
    _/\_/\_/\__  _/_/\_/\_/\_/\_/\_/\_/\_/\_/\_
    |  |  |  |( (  |  |  |  |  |  |  |  |  |  |
    |  |  |  | ) ) |  |  |  |  |  |  |  |  |  |
    |  |  |  |(_(  |  |  |  |  |  |  |  |  |  |
    |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
    |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
                                _.---.
                      |\---/|  / ) ca|
          ------------;     |-/ /|foo|---
                      )     (' / `---'
          ===========(       ,'==========
          ||   _     |      |
          || o/ )    |      | o
          || ( (    /       ;
          ||  \ `._/       /
          ||   `._        /|
          ||      |\    _/||
        __||_____.' )  |__||____________
         ________\  |  |_________________
                  \ \  `-.
                   `-`---'  hjw
            _,'|             _.-''``-...___..--';)
           /_ \'.      __..-' ,      ,--...--'''
          <\    .`--'''       `     /'
           `-';'               ;   ; ;
     __...--''     ___...--_..'  .;.'
    (,__....----'''       (,..--''
                           ;\
                          _' \_
                        ,' '  '`.
                       ;,)       \
                      /          :
                      (_         :
                       `--.       \
                          /        `.
                         ;           `.
                        /              `.
                       :                 `.
                       :                   \
                        \\                  \
                         ::                 :
                         || |               |
                         || |`._            ;
                        _;; ; __`._,       (________
                      ((__/(_____(______,'______(___)
     ____
    (.   \
      \  |   
       \ |___(\--/)
     __/    (  . . )
    "'._.    '-.O.'
         '-.  \ "|\
            '.,,/'.,,
```
