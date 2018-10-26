# StopWatch
StopWatch任务执行时间监视器

   StopWath是apache commons lang3包下的一个任务执行时间监视器

    

    主要方法:

    start();     //开始计时

    split();     //设置split点

    getSplitTime();  //获取从start 到 最后一次split的时间

    reset();     //重置计时

    suspend();     //暂停计时, 直到调用resume()后才恢复计时

    resume();      //恢复计时

    stop();      //停止计时

    getTime();    //统计从start到现在的计时