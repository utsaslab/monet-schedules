# MONeT schedule zoo
Pre-solved schedule for [MONeT](https://github.com/utsaslab/MONeT)

`solution_[model]_[batch_size]_[mode]_[budget].pkl` present in `monet_[model]_[batch_size]_24hr/` is a pre-solved MONeT schedule to run [model] with [batch_size] with a memory budget of [budget] GB using MONeT mode [mode]. 


`cost_[model]_[batch_size]_[mode].pkl` gives the profiled memory, workspace memory, and compute cost for model 	[model] using a batch of size [batch_size] and MONeT mode [mode], when profiled on a 16GB P100 GPU.

