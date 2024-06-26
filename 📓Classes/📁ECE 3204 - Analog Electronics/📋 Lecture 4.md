# BJT Amplifiers

![[2024-01-29 1 1]]
$\LARGE G_m=$ Transconductance of whole circuit
$\LARGE G_m=\frac{\partial i_o}{\partial v_i}|_{v_o=0}=\frac{g_m}{1+g_mR_E}$

$\LARGE R_T=$ Driving Point Resistance
$\LARGE R_T=\frac{\partial v_o}{\partial i_o}|_{i_i=0}$ (open circuit input)

$\LARGE A_V=G_m\cdot R_T$

## Common Emitter
![[2024-01-29_0 1|1000]]
KCL @ Base
$\LARGE \frac{v_{b}-v_s}{R_S}+\frac{v_{b}}{R_E}+\frac{v_be}{r_\pi}=0$

KCL @ Emitter
$\LARGE \frac{v_{eb}}{r_\pi}+\frac{v_e}{R_E}+g_mv_{be}+\frac{v_e-v_o}{r_o}+\frac{v_e-v_o}{R_C}=0$

$\LARGE \frac{v_o}{v_i}=-\frac{R_1//R_2//[(\beta+1)R_E+r_\pi]}{R_S+R_1//R_2//[(\beta+1)R_E+r_\pi]}\cdot\frac{g_m}{1+g_mR_E}\cdot (R_C//(r_o(1+g_mR_E))$

![[2024-01-29_1 1]]


$\LARGE g_mv_{be}-i_o-v_eg_o=0$

if $r_\pi>>R_E$
$\LARGE g_mv_{be}-i_o-i_oR_Eg_o=0$

$\LARGE g_mv_{be}-i_o(1+R_Eg_o)=0$

$\LARGE v_b=(v_i-v_e)\frac{r_\pi}{R_B+r_\pi}$

$\LARGE \frac{i_o}{v_i}=G_m\approx\frac{g_m}{1+g_mR_E}$

$\LARGE R_T\approx r_o(1+g_mR_E)//R_C$

## Common Base
![[2024-01-29_2 1|1000]]

#todo: clean this up lmfao


TLDR:

$\LARGE G_m=g_m$

$\LARGE R_T=r_o(1+g_mR_E)//R_C$

if $R_C<<\infty$
$\LARGE V_D=\frac{r_m//R_E}{E_S+r_m//R_E}$
