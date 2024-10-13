# Keychron K4v2

K4v2 Gateron RGB with VIA support + Custom SOCD library

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb keychron/k4/v2/rgb/ansi -km viaxsocd
    
* * *

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

# Changelog
20241009:
Today I found out about the enum blender_keycode {...!} thing that lets you define custom keycodes in keymap.c
I created the keycodes SOCD_A, SOCD_B, C, D respectively. based on their useage in the Socd_cleaner_t thing, they now have that behavior programmed to them. 
Now i just need to figure out a way to assign KC_A, KC_D to them using VIA shouldn't be too hard.