# lab_config
cs472 Spring 2018 Lab

sim: ** starting performance simulation **
pow(12.0, 2.0) == 144.000000
pow(10.0, 3.0) == 1000.000000
pow(10.0, -3.0) == 0.001000
str: 123.456
x: 123.000000
str: 123.456
x: 123.456000
str: 123.456
x: 123.456000
123.456 123.456000 123 1000
sinh(2.0) = 3.62686
sinh(3.0) = 10.01787
h=3.60555
atan2(3,2) = 0.98279
pow(3.60555,4.0) = 169
169 / exp(0.98279 * 5) = 1.24102
3.93117 + 5*log(3.60555) = 10.34355
cos(10.34355) = -0.6068,  sin(10.34355) = -0.79486
x     0.5x
x0.5     x
x   0.5x
-1e-17 != -1e-17 Worked!
sim: ** simulation statistics **
sim_num_insn                 213688 # total number of instructions committed
sim_num_refs                  56897 # total number of loads and stores committed
sim_num_loads                 34103 # total number of loads committed
sim_num_stores           22794.0000 # total number of stores committed
sim_num_branches              38591 # total number of branches committed
sim_elapsed_time                  1 # total simulation time in seconds
sim_inst_rate           213688.0000 # simulation speed (in insts/sec)
sim_total_insn               232994 # total number of instructions executed
sim_total_refs                61921 # total number of loads and stores executed
sim_total_loads               37539 # total number of loads executed
sim_total_stores         24382.0000 # total number of stores executed
sim_total_branches            42768 # total number of branches executed
sim_cycle                    224267 # total simulation time in cycles
sim_IPC                      0.9528 # instructions per cycle
sim_CPI                      1.0495 # cycles per instruction
sim_exec_BW                  1.0389 # total instructions (mis-spec + committed) per cycle
sim_IPB                      5.5372 # instruction per branch
IFQ_count                    352035 # cumulative IFQ occupancy
IFQ_fcount                    73988 # cumulative IFQ full count
ifq_occupancy                1.5697 # avg IFQ occupancy (insn's)
ifq_rate                     1.0389 # avg IFQ dispatch rate (insn/cycle)
ifq_latency                  1.5109 # avg IFQ occupant latency (cycle's)
ifq_full                     0.3299 # fraction of time (cycle's) IFQ was full
RUU_count                   1439861 # cumulative RUU occupancy
RUU_fcount                    45167 # cumulative RUU full count
ruu_occupancy                6.4203 # avg RUU occupancy (insn's)
ruu_rate                     1.0389 # avg RUU dispatch rate (insn/cycle)
ruu_latency                  6.1798 # avg RUU occupant latency (cycle's)
ruu_full                     0.2014 # fraction of time (cycle's) RUU was full
LSQ_count                    315220 # cumulative LSQ occupancy
LSQ_fcount                     5107 # cumulative LSQ full count
lsq_occupancy                1.4056 # avg LSQ occupancy (insn's)
lsq_rate                     1.0389 # avg LSQ dispatch rate (insn/cycle)
lsq_latency                  1.3529 # avg LSQ occupant latency (cycle's)
lsq_full                     0.0228 # fraction of time (cycle's) LSQ was full
sim_slip                    1964809 # total number of slip cycles
avg_sim_slip                 9.1948 # the average slip between issue and retirement
bpred_bimod.lookups           44162 # total number of bpred lookups
bpred_bimod.updates           38591 # total number of updates
bpred_bimod.addr_hits         34559 # total number of address-predicted hits
bpred_bimod.dir_hits          35148 # total number of direction-predicted hits (includes addr-hits)
bpred_bimod.misses             3443 # total number of misses
bpred_bimod.jr_hits            3426 # total number of address-predicted hits for JR's
bpred_bimod.jr_seen            3543 # total number of JR's seen
bpred_bimod.jr_non_ras_hits.PP           28 # total number of address-predicted hits for non-RAS JR's
bpred_bimod.jr_non_ras_seen.PP           41 # total number of non-RAS JR's seen
bpred_bimod.bpred_addr_rate    0.8955 # branch address-prediction rate (i.e., addr-hits/updates)
bpred_bimod.bpred_dir_rate    0.9108 # branch direction-prediction rate (i.e., all-hits/updates)
bpred_bimod.bpred_jr_rate    0.9670 # JR address-prediction rate (i.e., JR addr-hits/JRs seen)
bpred_bimod.bpred_jr_non_ras_rate.PP    0.6829 # non-RAS JR addr-pred rate (ie, non-RAS JR hits/JRs seen)
bpred_bimod.retstack_pushes         3906 # total number of address pushed onto ret-addr stack
bpred_bimod.retstack_pops         4529 # total number of address popped off of ret-addr stack
bpred_bimod.used_ras.PP         3502 # total number of RAS predictions used
bpred_bimod.ras_hits.PP         3398 # total number of RAS hits
bpred_bimod.ras_rate.PP    0.9703 # RAS prediction rate (i.e., RAS hits/used RAS)
il1.accesses                 255908 # total number of accesses
il1.hits                     239804 # total number of hits
il1.misses                    16104 # total number of misses
il1.replacements              15593 # total number of replacements
il1.writebacks                    0 # total number of writebacks
il1.invalidations                 0 # total number of invalidations
il1.miss_rate                0.0629 # miss rate (i.e., misses/ref)
il1.repl_rate                0.0609 # replacement rate (i.e., repls/ref)
il1.wb_rate                  0.0000 # writeback rate (i.e., wrbks/ref)
il1.inv_rate                 0.0000 # invalidation rate (i.e., invs/ref)
dl1.accesses                  56894 # total number of accesses
dl1.hits                      56344 # total number of hits
dl1.misses                      550 # total number of misses
dl1.replacements                 65 # total number of replacements
dl1.writebacks                   61 # total number of writebacks
dl1.invalidations                 0 # total number of invalidations
dl1.miss_rate                0.0097 # miss rate (i.e., misses/ref)
dl1.repl_rate                0.0011 # replacement rate (i.e., repls/ref)
dl1.wb_rate                  0.0011 # writeback rate (i.e., wrbks/ref)
dl1.inv_rate                 0.0000 # invalidation rate (i.e., invs/ref)
ul2.accesses                  16715 # total number of accesses
ul2.hits                      15494 # total number of hits
ul2.misses                     1221 # total number of misses
ul2.replacements                  0 # total number of replacements
ul2.writebacks                    0 # total number of writebacks
ul2.invalidations                 0 # total number of invalidations
ul2.miss_rate                0.0730 # miss rate (i.e., misses/ref)
ul2.repl_rate                0.0000 # replacement rate (i.e., repls/ref)
ul2.wb_rate                  0.0000 # writeback rate (i.e., wrbks/ref)
ul2.inv_rate                 0.0000 # invalidation rate (i.e., invs/ref)
itlb.accesses                255908 # total number of accesses
itlb.hits                    255885 # total number of hits
itlb.misses                      23 # total number of misses
itlb.replacements                 0 # total number of replacements
itlb.writebacks                   0 # total number of writebacks
itlb.invalidations                0 # total number of invalidations
itlb.miss_rate               0.0001 # miss rate (i.e., misses/ref)
itlb.repl_rate               0.0000 # replacement rate (i.e., repls/ref)
itlb.wb_rate                 0.0000 # writeback rate (i.e., wrbks/ref)
itlb.inv_rate                0.0000 # invalidation rate (i.e., invs/ref)
dtlb.accesses                 57580 # total number of accesses
dtlb.hits                     57570 # total number of hits
dtlb.misses                      10 # total number of misses
dtlb.replacements                 0 # total number of replacements
dtlb.writebacks                   0 # total number of writebacks
dtlb.invalidations                0 # total number of invalidations
dtlb.miss_rate               0.0002 # miss rate (i.e., misses/ref)
dtlb.repl_rate               0.0000 # replacement rate (i.e., repls/ref)
dtlb.wb_rate                 0.0000 # writeback rate (i.e., wrbks/ref)
dtlb.inv_rate                0.0000 # invalidation rate (i.e., invs/ref)
sim_invalid_addrs                 0 # total non-speculative bogus addresses seen (debug var)
ld_text_base             0x00400000 # program text (code) segment base
ld_text_size                  91744 # program text (code) size in bytes
ld_data_base             0x10000000 # program initialized data segment base
ld_data_size                  13028 # program init'ed `.data' and uninit'ed `.bss' size in bytes
ld_stack_base            0x7fffc000 # program stack segment base (highest address in stack)
ld_stack_size                 16384 # program initial stack size
ld_prog_entry            0x00400140 # program entry point (initial PC)
ld_environ_base          0x7fff8000 # program environment base address address
ld_target_big_endian              0 # target executable endian-ness, non-zero if big endian
mem.page_count                   33 # total number of pages allocated
mem.page_mem                   132k # total size of memory pages allocated
mem.ptab_misses                  37 # total first level page table misses
mem.ptab_accesses           2018030 # total page table accesses
mem.ptab_miss_rate           0.0000 # first level page table miss rate
