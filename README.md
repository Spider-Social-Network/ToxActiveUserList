English | [简体中文](./README.zh-CN.md) 

# Tox active user list
If you want to find more friends on the Tox network, then leave your ToxID and say something to your future friends!

## File naming rules
Take TAUL_V1_General_1.yaml as an example:
- TAUL: fixed prefix, acronym for Tox Active User List
- _: Underscore, separator
- V1: content format version number, reserved for extension
- General: subject or category
- 1: Decimal numbering to prevent a single file from being too large

## Format description
The format of this list is very simple! Using YAML format, the field has only one ToxIDs, and the description uses comments because it is optional;
One line represents a user;

## Example
```
   ToxIDs:
     -412845005FACE3FAD0684D8FD9560C507550412412C7EEB357A4DC4C541733201F20CA3D015D # I am a program ape, but don't ask me to repair the computer!
     -B229B7BD68FC66C2716EAB8671A461906321C764782D7B3EDBB650A315F6C4581F20CA3D015D # I am a programmer, who can help me repair the computer?
```

## Rules
- Please always keep it simple. Thank you
- Please make sure you have ownership of the added ToxId and don't cause trouble to others;unless they are public, such as a robot
