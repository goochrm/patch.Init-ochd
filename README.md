# Electrosmith patch.Init() demo with the Expert Sleepers FHX-8CV, emulating the Ochd octal LFO

## Author

goochrm

## Description

Patch.Init and its PatchSM are cool but we may need more gate and CV outputs.  Expert Sleepers makes really nice expanders for the FH2 Fader Host.  These expanders give 8x gate outs (FHX-8GT) and 8x CV outs (FHX-8CV) and we can use them with Patch.Init by making a custom cable and writing some C++ code.

This code example isn't a finished application but is a simple proof of concept, which emulates the Instruo/Divkid Ochd octal LFO.  The code runs an infinite loop clocking 8x counters at different increments to generate sine waves at different frequencies.  The sine wave are outputted at eurorack modular voltage levels through the FHX-8CV.

This is not an official project of Electrosmith or of Expert Sleepers.