# PX915_partII
To replicate my results you will only need a laptop computer. 

Please download following modules before running this jupyter notebook: 
https://github.com/jcockayne/bayesian_pdes_private,
https://github.com/jcockayne/bayesian_design

To correctly install the modules please follow the following instructions: 
1. Make sure all the modules that are imported in the notebook are up to date apart from the ones mentioned above. If you are missing any of them use "pip install module name".
2. Type "git clone https://github.com/jcockayne/bayesian_design" in a directory that you have access to.
3. Change directory into the folder you just cloned and type "python3 setup.py develop".
4. Repeat for the module https://github.com/jcockayne/bayesian_pdes_private.
5. Git clone https://github.com/tmacmoto/PX915_partII.git and open the jupyter notebook.
6. Run all of the cells once (the run-time is around 30 seconds), then re-run the cells by changing the length_scale parameter to the appropriate value. It is important that you ran the code on the same observed locations and values (you might need to seed your random number).
7. Inspect the results.



In the case you are using the HetSys provided laptops with Linux operating system, follow these instructions: 
1. Type "git clone https://github.com/jcockayne/bayesian_design" in a directory that you have access to.
2. Change directory into the folder you just cloned and type "sudo python3 setup.py develop", if this shows that you are missing a module, type "sudo pip install missing module", then run "sudo python3 setup.py develop". 
3. Repeat for the module https://github.com/jcockayne/bayesian_pdes_private
4. Run the first cell which imports all the modules and for any of the misssing modules run "sudo pip install missing module".
5. Run all of the cells once (the run-time is around 30 seconds), then re-run the cells by changing the length_scale parameter to the appropriate value. It is important that you ran the code on the same observed locations and values (you might need to seed your random number).
6. Inspect the results.


Please note that the IPython.display module is just for the interactive plotting, which is not necessarly to reproduce the results, so can be commented out if you are having trouble installing it.
