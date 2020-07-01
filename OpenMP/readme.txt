
This folder has 4 files, one executable "fd_predador_prey", a modified code with openMP
"omp_fd_predador_prey.c", a file in .sbatch "fd_predador_prey.sbatch" and an outuput 
file named "output_fd_predador_prey" 

gcc version 4.8.5
Red Hat 4.8.5-39

for execution, file "omp_fd_predador_prey.c" is compiled with the command
gcc -fopenmp omp_fd_predador_prey.c -o fd_predador_prey 

once this command is done, proceed to run the executable named fd_predador_prey 
with "sbatch fd_predador_prey.sbatch"

this command generates the output file "output_fd_predador_prey" and "error_fd_predador_prey"
where if no errors are generated, the last file will be an empty file.