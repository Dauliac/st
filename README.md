# st
My personal st fork

## Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):
```
    make clean install
```

## Tweak
Edit the `config.h` to change the esthetic or keymap's st


## Keymaps

    XK_ANY_MOD           XK_Break       sendbreak
    ControlMask          XK_Print       toggleprinter
    ShiftMask            XK_Print       printscreen
    XK_ANY_MOD           XK_Print       printsel
    MODKEY|ShiftMask     XK_Prior       zoom
    MODKEY|ShiftMask     XK_Next        zoom
    MODKEY|ShiftMask     XK_Home        zoomreset
    ShiftMask            XK_Insert      selpaste
    MODKEY|ShiftMask     XK_Insert      clippaste
    MODKEY|ShiftMask     XK_C           clipcopy
    MODKEY|ShiftMask     XK_V           clippaste
    TERMMOD              XK_Num_Lock    numlock
    MODKEY               XK_Control_L   iso14755
    ShiftMask            XK_Page_Up     kscrollup
    ShiftMask            XK_Page_Down   kscrolldown
    MODKEY               XK_Page_Up     kscrollup
    MODKEY               XK_Page_Down   kscrolldown
    MODKEY                XK_k           kscrollup
    MODKEY               XK_j           kscrolldown
    MODKEY               XK_Up          kscrollup
    MODKEY               XK_Down        kscrolldown
    MODKEY               XK_u           kscrollup
    MODKEY               XK_d           kscrolldown
    MODKEY|ShiftMask     XK_K           zoom
    MODKEY|ShiftMask     XK_J           zoom
    MODKEY|ShiftMask     XK_U           zoom
    MODKEY|ShiftMask     XK_D           zoom
