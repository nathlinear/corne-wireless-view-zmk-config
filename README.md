// Tap ctrl for tab. Hold and it will hold ctrl, but after a delay. Use gaming
// mode for immediate ctrl. Alt-tabbing has no delay and always assumes the
// button is tab.
```
  colemak_layer {
    // ------------------------------------------------------------------------------------
    // | ESC        |  Q  |  W  |  F  |  P  |  G  |   |  J  |  L  |  U  |  Y  |  ;  |  -  |
    // | CTRL (TAB) |  A  |  R  |  S  |  T  |  D  |   |  H  |  N  |  E  |  I  |  O  |  '  |
    // | SHFT       |  Z  |  X  |  C  |  V  |  B  |   |  K  |  M  |  ,  |  .  |  /  | RET |
    //                          | ALT | LWR | SPC |   | BKS | RSE | GUI |
```

```
  qwerty_layer {
      // -----------------------------------------------------------------------------
      // |     |  Q  |  W  |  E  |  R  |  T  |   |  Y  |  U  |  I  |  O  |  P  |     |
      // |     |  A  |  S  |  D  |  F  |  G  |   |  H  |  J  |  K  |  L  |  ;  |     |
      // |     |  Z  |  X  |  C  |  V  |  B  |   |  N  |  M  |  ,  |  .  |  /  |     |
      //                   |     |     |     |   |     |     |     |
```

// Makes ctrl work immediately, but tapping it for tab does not work.
// Alt-tabbing, however, still functions normally
```
  gaming_layer {
      // ------------------------------------------------------------------------------
      // |      |     |     |     |     |     |   |     |     |     |     |     |     |
      // | CTRL |     |     |     |     |     |   |     |     |     |     |     |     |
      // |      |     |     |     |     |     |   |     |     |     |     |     |     |
      //                    |     |     |     |   |     |     |     |
```

// Contains a dedicated Tab key, number keys, arrow keys, some navigation, and
// common text editing commands (backspace, delete, and enter on left hand)
```
  lower_layer {
      // ---------------------------------------------------------------------------------
      // |     |  1  |  2  |  3  |  4  |  5  |   |  6   |  7   |  8   |  9  |  0  | "|" |
      // |     | TAB |  ~  |  -  | BKS | DEL |   | LFT  | DWN  |  UP  | RGT |     |     |
      // |     |     |     |     | ENT |     |   | HOME | PGDN | PGUP | END |     |     |
      //                   |     |     |     |   |      |      |      |
```

// Contains symbols
```
  raise_layer {
      // -----------------------------------------------------------------------------
      // |     |  !  |  @  |  #  |  $  |  %  |   |  ^  |  &  |  *  |  (  |  )  |     |
      // |     |     |     |     |     |     |   |  -  |  =  |  [  |  ]  |  \  |  `  |
      // |     |     |     |     |     |     |   |  _  |  +  |  {  |  }  | "|" |  ~  |
      //                   |     |     |     |   |     |     |     |
```

// Press both LOWER and RAISE to activate layer. Contains function keys,
// bluetooth control, volume control, and default keymap control. Note: the
// gaming layer is toggle-based and works for both COLEMAK and QWERTY. It only
// changes the tab behavior. If you are tapping ctrl but tab is not being sent,
// try toggling the gaming layer to see if it was previously enabled.
```
  function_layer {
      // ---------------------------------------------------------------------------------------------------
      // |     |  F1   |  F2  |  F3  |  F4  |  F5  |   |  F6   |  F7    |  F8   |  F9   |  F10  |          |
      // |     |  BT1  | BT2  | BT3  | BT4  | BT5  |   |COLEMAK|  F11   |  F12  |       |       | VOL_UP   |
      // |     | BTCLR |      |      |      |      |   |QWERTY | GAMING |       |       |       | VOL_DOWN |
      //                      |      |      |      |   |       |        |       |
```