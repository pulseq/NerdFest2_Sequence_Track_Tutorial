# Sequences for the track *Pulse Sequence Design*
* Note: the notebook filename with suffix "_ex" is for the hands-on exercise, and with suffix "_sol" is the corresponding solution.

The goal of the *Pulse Sequence Design* course is to build several educational and time-optimized sequences, including 2D and 3D spin-echo (SE) and 2D and 3D gradient-echo (GRE) sequences for the portable scanner. The intermediate steps to reach this goal in the hands-on exercise are listed below:

## Basic MR spectroscopy
* `s00_fid`: the simplest free induction decay (FID) sequence.
* `s01_from_fid_to_1d_se`: extend the FID sequence to SE sequence with 1D spatial encoding.
## First imaging basics 
* `s02_from_1d_se_to_2d_radial` : convert the 1D SE to a simple radial imaging sequence
* `s03_from_fid_to_gre1d` : first step towards imaging with gradient echos
* `s04_from_gre1d_to_fully_relaxed_gre2d` : a simplest 2D gradient echo (without spoiling)

# WORKS IN PROGRESS beyond this point
## 3D SE sequence
* `s10_from_1d_se_to_3d_se`: extend the 1D SE to 3D SE.
* `s11_optimized_3d_se`: optimize the 3D SE by doing "gradient surgery" with function `pp.make_extended_trapezoid`.
* `s12_optimized_3d_se_portableScanner`: adapt the optimized 3D SE for the data acquisition on the portable scanner.
## T2 mapping
* `s20_optimized_3d_mse_portableScanner`: extend the optimized 3D SE adapted for the portable scanner from single-echo to multi-echo for T2 mapping.
