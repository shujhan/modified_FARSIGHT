# modified_FARSIGHT
module load nvhpc-openmpi4/22.3 cuda/11.3 

module load eigen boost 

cmake .. -D CMAKE_CXX_COMPILER=nvc++
