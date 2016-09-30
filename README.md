# sample

{
  "version": 1,
  "schedule": {
    "type": "simple",
    "interval": "2s"
  },
  "workflow": {
    "collect": {
      "metrics": {
		"/intel/docker/*/stats/cgroups/cpu_stats/cpu_usage/percpu_usage/*/value" : {},
		"/intel/docker/*/stats/cgroups/cpu_stats/cpu_usage/total_usage" : {},
		"/intel/docker/*/stats/cgroups/cpu_stats/cpu_usage/usage_in_kernelmode" : {},
		"/intel/docker/*/stats/cgroups/memory_stats/stats/total_pgmajfault" : {},
		"/intel/docker/*/stats/cgroups/memory_stats/stats/total_pgpgin" : {},
		"/intel/docker/*/stats/cgroups/memory_stats/stats/total_pgpgout" : {},
		"/intel/docker/*/stats/connection/tcp/established" : {},
		"/intel/docker/*/stats/connection/tcp/syn_recv" : {},
		"/intel/docker/*/stats/connection/tcp/syn_sent" : {},
		"/intel/docker/*/stats/filesystem/*/available" : {},
		"/intel/docker/*/stats/filesystem/*/base_usage" : {},
		"/intel/docker/*/stats/network/*/tx_dropped" : {},
		"/intel/docker/*/stats/network/*/tx_errors" : {},
		"/intel/docker/*/stats/network/*/tx_packets" : {}
      },
      "config": {}
    }
  }
}
