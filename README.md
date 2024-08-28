# Stage3: Parallelized Image Retrieval and Classification

**Required Inputs:**
1) config_files/ neuron_<neuron_id>_results_ecii_V2.txt     (Path: /homes/samatha94/ExAI_inputs_and_outputs/Stage1_Results/config_files)
2) model_resnet50V2_10classes_retest2023June.h5             (Path: "/homes/samatha94/ExAI_inputs_and_outputs/Stage1_Results/model_resnet50V2_10classes_retest2023June.h5")


**Expected Outputs:**                  (Path: /homes/samatha94/ExAI_inputs_and_outputs/Stage3_Results)
1) Google_images
2) evaluation/neuron<neuron_id>_solution<solution_id>_evaluation_set.csv
3) verification/neuron<neuron_id>_solution<solution_id>_verification_set.csv



**Bash file name:** job_stage3.sh

**Bash Command to kick off the job:** sbatch job_stage3.sh

**Bash command to check the status of the job:** 

sacct --format=JobID,JobName,State,ReqMem,MaxRSS,Start,End,TotalCPU,Elapsed,NCPUS,NNodes,NodeList --jobs= <job_id>

**Log file:** my_job_output_<job_id>.txt (Path: /homes/samatha94/)

**Bash Command to cancel the job:** scancel job_id


