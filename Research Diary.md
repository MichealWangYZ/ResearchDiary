We applied strain on both direction, one along the zigzag chain and another perpendicular to it.

![image-20220928142007732](/Users/mac/Library/Application Support/typora-user-images/image-20220928142007732.png)

And by calculating it and fit the solutions with polynomials (because it is safe to assume that it behaves like this close to convergence point)

![perp](/Users/mac/Desktop/perp.bmp)

![para](/Users/mac/Desktop/para.bmp)

I also checked the system by letting the magnetic dipoles to point to y direction and they are roughly the same, the difference is within 1meV.





Fe(Mn)PSe3 Di Xiao, Xiaodong Xu Nano Letter



Turn the U to be 6 rather than 6.4

The energy difference would be 6.8 meV, which is roughly the same.



##### Calculations of  $MoS_2$ band structure



<img src="/Users/mac/structure/MoS2/band2.png" alt="band2" style="zoom:36%;" />

Both SOC and DFTU are not included. There are 25 kpoints per line. A direct bandgap of about 1.6 eV is observed at K point, in contrast to the indirect bandgap observed&calculated in Bulk Materials.





##### Potential Problems on inplane anisotropy

I don't think it is a significant problem since the magnetic energy is of the order of 0.1 eV, compared with the 1 meV that we found in the difference between two.



The energies of two states are roughly:

|      | Para(eV) | Perp(eV) |
| ---- | -------- | -------- |
| 1%   | -88.8214 | -88.8220 |
| 2%   | -88.7806 | -88.7821 |
| 3%   | -88.7160 | -88.7183 |
| 4%   | -88.6293 | -88.6335 |
| 5%   | -88.5234 | -88.5295 |

$E_{relax}$=-88.8423eV![delta](/Users/mac/structure/NiPS3/delta.bmp)The relation, for me, is pretty unclear, although I didn't figure out why.

<img src="/Users/mac/structure/NiPS3/Ene-Strain.bmp" alt="Ene-Strain" style="zoom:50%;" />

Since the Convergence is pretty difficult, I decided to take another approach to argue that the energy difference is mainly caused by the magnetic sturcture rather than electronic structure. 

With the relaxed state of strain applied on both the direction spin is also turned off. Results showed that the energy difference is around 0.6 meV, compared with 6 meV that we have seen in systems with zigzag antiferromagnetism. It's worthnoting that the energy difference casued by structure is around 0.3 eV, 0.6 meV seems like a reasonable structural energy difference caused by zigzag antiferromagnetism.



I believe that the existence of Ni is very important here. I'm not sure about that even if I have checked some articles.The SOC here is indeed very small, but I'm feeling like zigzag AFM is already because of the competition between nearest neighbor and second nerest neighbor. 

In the fully relaxed version, the energy difference between two states is roughly 0.23 eV. Compared with the energy difference of 6 meV, a 5% strain would lead to around 3% difference in magnetic energy is sensible. This also address Professor Yang's Concern that it is a very large change in coupling constants: Yes indeed that's very large for materials such as $CrX_3$ but may not be very significant for materials like $NiPS_3$, where $Ni$ atom, a famous material for ferromagnetism plays a strong role.

<img src="/Users/mac/Library/Application Support/typora-user-images/image-20221012010037553.png" alt="image-20221012010037553" style="zoom:50%;" />

(I didn't do very serious calculations because I just want to use these results to argue that my results is solid)