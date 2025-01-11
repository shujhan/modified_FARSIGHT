# modified_FARSIGHT
module load nvhpc-openmpi4/22.3 cuda/11.3 

module load eigen boost 

cmake .. -D CMAKE_CXX_COMPILER=nvc++

make 

After getting the compiled file farrsight_cpu and farrsight_gpu, use python interface and .sh file to run different jobs.

Templates are in new_interface folder(Strong_LD_amr), which includes 7 files in total, 1 deck file, 1 python file, 3 .sh files and the compiled farrsight files. More .sh files can be written if needed. 

Examples and results are in 
