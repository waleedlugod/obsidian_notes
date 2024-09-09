The overall performance improvement gained by optimizing a single part of a system is limited by the fraction of time that the improved part is actually used.

speedup = performance_with_enhancement / performance_without_enhancement
speedup = execution_time_without_enhancement / execution_time_with_enhancement

Fraction enhanced: the fraction of computation in the original machine that can be converted to take advantage of the enhancement; <= 1
Speedup enhanced: the improvement gained by the enhanced execution mode; > 1

exec_time_new = exec_time_old( (1 - fraction_enhanced) + fraction_enhanced / speedup_enhanced)
speedup_overall = exec_time_old / exec_time_new
speedup_overall = 1 / ( (1 - fraction_enhanced) + fraction_enhanced / speedup_enhanced )

Little's law
L = λW
L = work in progress
λ = arrival rate
W = wait time