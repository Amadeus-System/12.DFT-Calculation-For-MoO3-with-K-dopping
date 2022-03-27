# 12.DFT-Calculation-For-MoO3-with-K
Repository for my DFT Research of MoO3 + K dopping in the surface using Openmx3.9

본 연구에서는 2차원 MoO3 표면에 포타슘(K)이 결합하였을때 결합 밀도에 따른 Work functio 변화를 조사하였다.
Openmx3.9 버전을 이용하여 DFT 계산을 수행하였으며 계산상의 제한조건을 해결하고 실제 물리적 해에 가까운 계산결과를 얻기 위해 empty layer를 최대 5층까지 추가하여
work function의 수렴성을 확인하였다.

1. VESTA를 이용한 결정구조를 시각화하고 유닛셀을 적합하게 디자인하였다.
2. DFT의 Geometry optimization을 수행하여 Moo3 표면에 결합하는 K의 자연스러운 좌표를 추정하였다.
3. Empty layer를 최대 5층까지 K 위에 추가하여 진공에서의 파동함수의 불연속성을 연속성으로 변화시켰다.
4. 최종적으로 Moo3 표면에서 K 결합밀도에 따른 work function의 값이 감소하고, 특정한 값으로 수렴함을 확인할 수 있었다.

![DFT configuration](https://drive.google.com/uc?export=view&id=1ffrWYh_TrJFp0cyS6UgZ7s0-KosRhaku)

## Overview:
## Ab-initio material simulations by **density functional theory (DFT)** and **dynamical mean-field theory (DMFT)** 
Quantum solid state and condensed matter problems are often challenging to directly solve, but still they can be treated via 'ab-initio' methods if proper approximations can be provided. We employ two electronic structure calculation methods, density functional theoy (DFT) and dynamical mean-field theory (DMFT), tackling both the weakly and strongly correlated electronic systems respectively.
