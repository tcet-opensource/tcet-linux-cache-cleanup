#!/bin/env bash

sudo pacman -Sc
sudo pacman -Scc

paccache -r
sudo pacman -R $(pacman -Qtdq)

rm -rf ~/.cache/*
rm -rf ~/.local/share/Trash/*
