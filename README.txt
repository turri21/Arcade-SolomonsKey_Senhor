-=(SolomonsKey_Senhor notes)=-

Tested: Working Video 720p, 1080p & Sound.

---------------------------------------------------------------------------------
-- 
-- Arcade: Solomon's Key  port to MiSTer by MiSTer-X
-- 17 November 2019
--
-- https://github.com/MrX-8B/MiSTer-Arcade-SolomonsKey
-- 
---------------------------------------------------------------------------------
-- FPGA Solomon's Key for Spartan-6
------------------------------------------------
-- Copyright (c) 2014 MiSTer-X
---------------------------------------------------------------------------------
-- T80/T80s - Version : 0242
-----------------------------
-- Z80 compatible microprocessor core
-- Copyright (c) 2001-2002 Daniel Wallner (jesus@opencores.org)
---------------------------------------------------------------------------------
-- YM2149 (AY-3-8910)
-- Copyright (c) MikeJ - Jan 2005
---------------------------------------------------------------------------------
-- MRA files
----------------------------------------------
-- written by Bruno Silva (@eubrunosilvapt)
-------------------------------------------------------------------------------------------
-- 
-- 
-- Keyboard inputs :
--
--   F2          : Coin + Start 2 players
--   F1          : Coin + Start 1 player
--   UP,DOWN,LEFT,RIGHT arrows : Movements
--   SPACE       : Stone
--   CTRL        : Fire
--
-- MAME/IPAC/JPAC Style Keyboard inputs:
--   5           : Coin 1
--   6           : Coin 2
--   1           : Start 1 Player
--   2           : Start 2 Players
--   R,F,D,G     : Player 2 Movements
--   A           : Player 2 Stone
--   S           : Player 2 Fire
--
-- Joystick support.
--
--
---------------------------------------------------------------------------------

                                *** Attention ***

ROMs are not included. In order to use this arcade, you need to provide the
correct ROMs.

To simplify the process .mra files are provided in the releases folder, that
specifies the required ROMs with checksums. The ROMs .zip filename refers to the
corresponding file of the M.A.M.E. project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for
information on how to setup and use the environment.

Quickreference for folders and file placement:

/_Arcade/<game name>.mra
/_Arcade/cores/<game rbf>.rbf
/_Arcade/mame/<mame rom>.zip
/_Arcade/hbmame/<hbmame rom>.zip
