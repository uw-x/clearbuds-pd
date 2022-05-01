# ClearBuds: Wireless Binaural Earbuds for Learning-based Speech Enhancement
## Abstract
We present ClearBuds, the first end-to-end hardware and software system that utilizes a neural network to enhance speech streamed from two wireless earbuds. Real-time speech enhancement for wireless earbuds requires high-quality sound separation and background cancellation, operating in real-time and on a mobile phone. ClearBuds bridges state-of-the-art deep learning for blind audio source separation and in-ear mobile systems by making two key technical contributions: 1) a new wireless earbud design capable of operating as a synchronized, binaural microphone array, and 2) a lightweight dual-channel speech enhancement neural network that runs on a mobile device. Results show that our wireless earbuds achieve a synchronization error less than 64 us and our network has a runtime of 21.4 ms on an accompanying mobile phone. In-the-wild evaluation with eight users in previously unseen indoor and outdoor multipath scenarios demonstrates that our neural network generalizes to learn both spatial and acoustic cues to perform noise suppression and background speech removal. In a user-study with 37 participants who spent over 15.4 hours rating 1041 audio samples collected in-the-wild, our system achieves improved mean opinion score and background noise suppression.

## Contents
This directory contains the product design (mechanical housing) files for ClearBuds. 

Lid: shio_clearvoice_lid vXX.stl
Base design #1: shio_clearvoice vXX.stl
Base design #2: shio_clearvoice_meijunter_eartip vXX.stl
Base design #3: shio_clearvoice_white_eartip vXX.stl

## Hardware Setup
Use .stl files to 3D print enclosures. Generally resin printers that can achieve a submillimeter resolution will produce the best results for the small snap and hole features between the lid and base.

There are three base designs provided that each have different size shafts that interface with different eartip designs to accomodate different ear shapes and sizes. Base design #1 interfaces with Sony DR-EX12iP eartips. Base design #2 interfaces interfaces with JBL Reflect eartips as well as replacement ones such as Meijunter B01L3DM8Z2 (https://www.amazon.com/gp/product/B01L3DM8Z2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1). Base design #3 interfaces with Vezukv eartips NJEG-6W (https://www.amazon.com/gp/product/B07WFK8KVJ/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1). The wing of these last two eartips generally help the earbuds sit more stably across different ear shapes. 
