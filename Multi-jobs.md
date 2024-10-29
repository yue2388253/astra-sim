The command to run multi-jobs experiment:

- single job
```shell
{exeuctable}
--multi-jobs-configuration=inputs/multi_jobs/single_job.json
--system-configuration=inputs/system/Ring.json
--remote-memory-configuration=inputs/remote_memory/analytical/memory_pool_expansion.json
--logical-topology-configuration=inputs/network/ns3/sample_8nodes_1D.json
--comm-group-configuration=inputs/comm_group/4in8.json
--network-configuration=extern/network_backend/ns-3/scratch/config/config_cassini.txt
```

- multi jobs
```shell
{exeuctable}
--multi-jobs-configuration=inputs/multi_jobs/lam1_lam2.json
--system-configuration=inputs/system/Ring.json
--remote-memory-configuration=inputs/remote_memory/analytical/memory_pool_expansion.json
--logical-topology-configuration=inputs/network/ns3/sample_8nodes_1D_1.json
--comm-group-configuration=inputs/comm_group/8nodes_2jobs.json
--network-configuration=extern/network_backend/ns-3/scratch/config/config_lam.txt
```