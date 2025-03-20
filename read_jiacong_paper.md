
1. nMOS 指向内， pMOS指向外
2. 符号相连的一端叫做S极，控制端叫做G极，我们主要参考Vgs之间的电压
3. for nMOS, Vgs_current > Vgs_ref, then the mos will open, 工作在哪个区？
4. for pMOS, Vgs_current < Vgs_ref, then the mos will open
5. the R4 branch of the circuit is for provide a Von to Gate of M1 keep the M1 to open, same as the diode branch of the LDO feed back circuit
6. the R1 and R2 is to adjut a threathold to open the M1, when the M1 open, the gate of the M2 will be drag to GND, (which before is the Vcst?) to make the M2 open, and it will make the M3 to open
7. what does the meaning of the M3? seems it is used for cut out the voltage
8. which direction does the diode in mos point for
9. ** Where vthln and vthlp are the voltage drop of the MOSFETs
when they are diode-connected to a current source. **