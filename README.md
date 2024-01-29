**Brief description**

(i) EggsinEggs is a mechanical model for establishing the force-displacement relationships of a physical object, programmed in Python 3. It is under development and will be updated in the future.
(ii) It aims to help the numerical calculation in terms of cyclic loading and long-term prediction. It is fast and easy to use. Details of how to use this programme will be given at “Documentaiton.pdf”
(iii) This programme is provided for academic and research purposes only, not for any commercial use. User can modify and improve this programme, only if the modifications are also open sourced. The author wishes all user can work together to improve the programme.
(iv)Mistakes may be found in the codes because now it is only a one-man’s work. If you find anything wrong in the codes, please let the author know. Appreciate a lot.

**Have you seen an egg inside an egg?**
Although quite rare, it is happened occasionally all around the world that a hen may have a giant egg with another tiny egg inside, as some pictures and videos were uploaded to the internet:
 ![image](https://github.com/KadeFrank/EggsinEggs/assets/125382994/2796bf2b-d6d5-40f7-a2a8-64cf0415fb2f)
https://youtu.be/_wubgAIiWpY
https://youtu.be/FLt7bLIgv9o
https://youtu.be/5oetf4SETsw

**What’s the connection between the weird egg with this project?**

Herein, we are not intended to discuss the biology problem but only use it to understand the appearance of our mathematical model. This project is trying to establish the relationship between the forces and displacements of an object, which may be a foundation or structure. Imagine if there’s more eggs, layers insider layers. And a bug is lay at the centre, marked as the red point O, as shown below. 
  
Now the bug starts from point O, as shown below, moving until reaches the shell of the the inner-most egg at point A, and then it drags the eggshell along with it until reaches another shell at point B, then point C and D. Afterwards, the bug turns to the opposite direction, through E, F and G, to H.
  	  
 	 
The moving distance represents the forces applied to this object, and the corresponding displacement is obtained by the damping property of the mobilized eggshells, which is defined in the model. Now, a very simple force-displacement (F-u) relationship is established, as shown below.
 
The model originates from the Iwan model (Iwan, 1967) and has been adopted by recent research of the foundations of offshore foundations (Houlsby et al., 2017; Page et al., 2017; 2018; Skau et al., 2018; Zhang et al., 2023). The model presented in Houlsby et al. (2017) is already open sourced on github as the HyperDrive:
https://github.com/guyhoulsby/HyperDrive/tree/master

**What can this model do?**

This model is originally established for simulating the single bucket (as shown below) of multi-bucket foundations of offshore wind turbines. Hysteric loops and damping ratios can be predicted under cyclic loading. The soil softening and anisotropy is considered. With very high computational efficiency, the load-displacement relationships for 1000 cycles of cyclic loading are predicted in 10 minutes, overcame the drawbacks of the traditional Finite-element method.
 
**Reference**

Houlsby, G. T., Abadie, C. N., Beuckelaers, W. J. A. P., & Byrne, B. W. (2017). A model for nonlinear hysteretic and ratcheting behaviour. International Journal of Solids and Structures, 120, 67-80.
Iwan, W. D. (1967). On a class of models for the yielding behavior of continuous and composite systems. J. Appl. Mech. 34, 612-617.
Page, A. M., Grimstad, G., Eiksund, G. R., Jostad, H. P. (2018). A macro-element pile foundation model for integrated analyses of monopile-based offshore wind turbines. Ocean Engineering, 167:23–35.
Page, A. M., Skau, K. S., Jostad, H. P., & Eiksund, G. R. (2017). A new foundation model for integrated analyses of monopile-based offshore wind turbines. Energy Procedia, 137, 100-107.
Skau, K. S., Grimstad, G., Page, A. M., Eiksund, G. R., & Jostad, H. P. (2018). A macro-element for integrated time domain analyses representing bucket foundations for offshore wind turbines. Marine Structures, 59, 158-178.
Zhang, C., Wang, D., & Zheng, J. (2023). A cyclic-softening macro element model for mono-bucket foundations supporting offshore wind turbines in clay. Computers and Geotechnics, 161, 105603.

