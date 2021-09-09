# PX915_partII
Can download peer to peer UQ exercise file

Please download following modules before running this jupyter notebook: 
https://github.com/jcockayne/bayesian_pdes_private
https://github.com/jcockayne/bayesian_design

To correctly install the modules please follow the following instructions: 
1. Make sure all the modules that are imported in the notebook are up to date apart from the ones mentioned above. If you are missing any of them use "pip install module name"
3. Type "git clone https://github.com/jcockayne/bayesian_design" in a directory that you have access to.
4. Change directory into the folder you just cloned and type "python3 setup.py develop".
5. Repeat for the module https://github.com/jcockayne/bayesian_design.
6. Git clone https://github.com/tmacmoto/PX915_partII.git and open the jupyter notebook.
7. Run all of the cells once, then re-run the cells by changing the length_scale parameter to the appropriate value. It is important that you ran the code on the same observed locations and values (you might need to seed your random number).
8. Inspect the results.

In the case you are using the HetSys provided laptops with Linux operating system: follow everything the same until step 3. 
4. Change directory into the folder you just cloned and type "sudo python3 setup.py develop", if this shows that you are missing a module, type "sudo pip install missing module", then run "sudo python3 setup.py develop". 
5. Carry out step 6
6. Run the first cell which imports all the modules and for any of the misssing modules run "sudo pip install missing module".
7. Everything should work fine now.
