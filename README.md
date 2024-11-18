```
[2024-11-18 17:40:43,833 submission_checker1.py:3109 INFO] Results=1, NoResults=0, Power Results=0
[2024-11-18 17:40:43,833 submission_checker1.py:3116 INFO] ---
[2024-11-18 17:40:43,833 submission_checker1.py:3117 INFO] Closed Results=0, Closed Power Results=0

[2024-11-18 17:40:43,833 submission_checker1.py:3122 INFO] Open Results=1, Open Power Results=0

[2024-11-18 17:40:43,833 submission_checker1.py:3127 INFO] Network Results=0, Network Power Results=0

[2024-11-18 17:40:43,833 submission_checker1.py:3132 INFO] ---
[2024-11-18 17:40:43,833 submission_checker1.py:3134 INFO] Systems=1, Power Systems=0
[2024-11-18 17:40:43,833 submission_checker1.py:3138 INFO] Closed Systems=0, Closed Power Systems=0
[2024-11-18 17:40:43,833 submission_checker1.py:3143 INFO] Open Systems=1, Open Power Systems=0
[2024-11-18 17:40:43,833 submission_checker1.py:3148 INFO] Network Systems=0, Network Power Systems=0
[2024-11-18 17:40:43,833 submission_checker1.py:3153 INFO] ---
[2024-11-18 17:40:43,833 submission_checker1.py:3158 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@cm4mlops/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType   | SystemName   | Platform                                                      | Model               | MlperfModel         | Scenario   |   Result | Accuracy                                                     |   number_of_nodes | host_processor_model_name        |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                    | framework   | operating_system                              | notes                             |   compliance |   errors | version   |   inferred | has_power   | Units     | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:-------------|:-------------|:--------------------------------------------------------------|:--------------------|:--------------------|:-----------|---------:|:-------------------------------------------------------------|------------------:|:---------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:------------------------------------------------------------------------------------------------------------|:------------|:----------------------------------------------|:----------------------------------|-------------:|---------:|:----------|-----------:|:------------|:----------|:--------------------|
|  0 | scc2           | available      | open       | datacenter   | f2ea47b0a016 | f2ea47b0a016-nvidia_original-gpu-tensorrt-vdefault-scc24-main | stable-diffusion-xl | stable-diffusion-xl | Offline    |  7.46497 | CLIP_SCORE: 16.63159880042076  FID_SCORE: 234.62921308614995 |                 1 | AMD EPYC 9754 128-Core Processor |                          2 |                         128 | NVIDIA H100 80GB HBM3    |                       6 | open/scc2/results/f2ea47b0a016-nvidia_original-gpu-tensorrt-vdefault-scc24-main/stable-diffusion-xl/offline | TensorRT    | Ubuntu 20.04 (linux-6.1.0-27-amd64-glibc2.31) | Automated by MLCommons CM v3.3.3. |            1 |        0 | v4.1      |          0 | False       | Samples/s | int8                |