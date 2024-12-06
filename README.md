# NIPPO
目前BC跑不起来 PPIL也是一样 
bc报错：
Traceback (most recent call last):                                                                                                                         
  File "d:\NIPPO\BC IQ\main.py", line 91, in <module>
    train(args)
  File "d:\NIPPO\BC IQ\main.py", line 24, in train
    make_buffer(expert_path, args.subsampling_num, args.subsampling_rate, args.use_absorb, args.truncated_len,
  File "d:\NIPPO\BC IQ\utils\data_utils.py", line 74, in make_buffer
    trajs = pickle.load(f)
_pickle.UnpicklingError: STACK_GLOBAL requires str

dmc接口现在还不清楚怎么写