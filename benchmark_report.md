# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.LoadBalancingBenchmark.testKafkaLoadBalancing

# Run progress: 0,00% complete, ETA 02:46:40
# Fork: 1 of 5
# Warmup Iteration   1: 0,967 ops/s
# Warmup Iteration   2: 0,992 ops/s
# Warmup Iteration   3: 0,988 ops/s
# Warmup Iteration   4: 0,994 ops/s
# Warmup Iteration   5: 0,991 ops/s
Iteration   1: 0,990 ops/s
Iteration   2: 0,989 ops/s
Iteration   3: 0,992 ops/s
Iteration   4: 0,989 ops/s
Iteration   5: 0,988 ops/s

# Run progress: 1,00% complete, ETA 02:49:14
# Fork: 2 of 5
# Warmup Iteration   1: 0,967 ops/s
# Warmup Iteration   2: 0,992 ops/s
# Warmup Iteration   3: 0,990 ops/s
# Warmup Iteration   4: 0,993 ops/s
# Warmup Iteration   5: 0,990 ops/s
Iteration   1: 0,989 ops/s
Iteration   2: 0,993 ops/s
Iteration   3: 0,991 ops/s
Iteration   4: 0,989 ops/s
Iteration   5: 0,990 ops/s

# Run progress: 2,00% complete, ETA 02:47:29
# Fork: 3 of 5
# Warmup Iteration   1: 0,968 ops/s
# Warmup Iteration   2: 0,989 ops/s
# Warmup Iteration   3: 0,991 ops/s
# Warmup Iteration   4: 0,992 ops/s
# Warmup Iteration   5: 0,991 ops/s
Iteration   1: 0,993 ops/s
Iteration   2: 0,991 ops/s
Iteration   3: 0,988 ops/s
Iteration   4: 0,990 ops/s
Iteration   5: 0,990 ops/s

# Run progress: 3,00% complete, ETA 02:45:46
# Fork: 4 of 5
# Warmup Iteration   1: 0,962 ops/s
# Warmup Iteration   2: 0,992 ops/s
# Warmup Iteration   3: 0,991 ops/s
# Warmup Iteration   4: 0,991 ops/s
# Warmup Iteration   5: 0,992 ops/s
Iteration   1: 0,993 ops/s
Iteration   2: 0,996 ops/s
Iteration   3: 0,990 ops/s
Iteration   4: 0,991 ops/s
Iteration   5: 0,990 ops/s

# Run progress: 4,00% complete, ETA 02:44:03
# Fork: 5 of 5
# Warmup Iteration   1: 0,967 ops/s
# Warmup Iteration   2: 0,992 ops/s
# Warmup Iteration   3: 0,990 ops/s
# Warmup Iteration   4: 0,987 ops/s
# Warmup Iteration   5: 0,991 ops/s
Iteration   1: 0,991 ops/s
Iteration   2: 0,991 ops/s
Iteration   3: 0,991 ops/s
Iteration   4: 0,990 ops/s
Iteration   5: 0,989 ops/s


Result "io.github.dziodzi.LoadBalancingBenchmark.testKafkaLoadBalancing":
  0,991 ▒(99.9%) 0,001 ops/s [Average]
  (min, avg, max) = (0,988, 0,991, 0,996), stdev = 0,002
  CI (99.9%): [0,989, 0,992] (assumes normal distribution)


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.LoadBalancingBenchmark.testRabbitMQLoadBalancing

# Run progress: 5,00% complete, ETA 02:42:21
# Fork: 1 of 5
# Warmup Iteration   1: 4,277 ops/s
# Warmup Iteration   2: 4,454 ops/s
# Warmup Iteration   3: 4,469 ops/s
# Warmup Iteration   4: 4,689 ops/s
# Warmup Iteration   5: 4,633 ops/s
Iteration   1: 4,218 ops/s
Iteration   2: 4,600 ops/s
Iteration   3: 4,271 ops/s
Iteration   4: 4,460 ops/s
Iteration   5: 4,696 ops/s

# Run progress: 6,00% complete, ETA 02:40:38
# Fork: 2 of 5
# Warmup Iteration   1: 4,002 ops/s
# Warmup Iteration   2: 4,186 ops/s
# Warmup Iteration   3: 4,433 ops/s
# Warmup Iteration   4: 4,694 ops/s
# Warmup Iteration   5: 4,121 ops/s
Iteration   1: 4,057 ops/s
Iteration   2: 4,734 ops/s
Iteration   3: 4,568 ops/s
Iteration   4: 4,285 ops/s
Iteration   5: 4,960 ops/s

# Run progress: 7,00% complete, ETA 02:39:03
# Fork: 3 of 5
# Warmup Iteration   1: 4,637 ops/s
# Warmup Iteration   2: 4,406 ops/s
# Warmup Iteration   3: 4,478 ops/s
# Warmup Iteration   4: 4,574 ops/s
# Warmup Iteration   5: 4,510 ops/s
Iteration   1: 4,804 ops/s
Iteration   2: 4,609 ops/s
Iteration   3: 4,579 ops/s
Iteration   4: 4,360 ops/s
Iteration   5: 4,287 ops/s

# Run progress: 8,00% complete, ETA 02:37:22
# Fork: 4 of 5
# Warmup Iteration   1: 4,777 ops/s
# Warmup Iteration   2: 4,194 ops/s
# Warmup Iteration   3: 4,599 ops/s
# Warmup Iteration   4: 4,767 ops/s
# Warmup Iteration   5: 4,707 ops/s
Iteration   1: 4,397 ops/s
Iteration   2: 4,059 ops/s
Iteration   3: 4,851 ops/s
Iteration   4: 4,306 ops/s
Iteration   5: 4,951 ops/s

# Run progress: 9,00% complete, ETA 02:35:43
# Fork: 5 of 5
# Warmup Iteration   1: 4,428 ops/s
# Warmup Iteration   2: 4,210 ops/s
# Warmup Iteration   3: 4,188 ops/s
# Warmup Iteration   4: 4,388 ops/s
# Warmup Iteration   5: 4,748 ops/s
Iteration   1: 5,093 ops/s
Iteration   2: 4,542 ops/s
Iteration   3: 4,314 ops/s
Iteration   4: 5,036 ops/s
Iteration   5: 4,487 ops/s


Result "io.github.dziodzi.LoadBalancingBenchmark.testRabbitMQLoadBalancing":
  4,541 ▒(99.9%) 0,220 ops/s [Average]
  (min, avg, max) = (4,057, 4,541, 5,093), stdev = 0,294
  CI (99.9%): [4,321, 4,761] (assumes normal distribution)


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.LoadBalancingMultipleConsumersBenchmark.testKafkaLoadBalancingMultipleConsumers

# Run progress: 10,00% complete, ETA 02:34:01
# Fork: 1 of 5
# Warmup Iteration   1: 0,323 ops/s
# Warmup Iteration   2: 0,331 ops/s
# Warmup Iteration   3: 0,330 ops/s
# Warmup Iteration   4: 0,331 ops/s
# Warmup Iteration   5: 0,330 ops/s
Iteration   1: 0,330 ops/s
Iteration   2: 0,331 ops/s
Iteration   3: 0,330 ops/s
Iteration   4: 0,330 ops/s
Iteration   5: 0,331 ops/s

# Run progress: 11,00% complete, ETA 02:35:01
# Fork: 2 of 5
# Warmup Iteration   1: 0,323 ops/s
# Warmup Iteration   2: 0,331 ops/s
# Warmup Iteration   3: 0,331 ops/s
# Warmup Iteration   4: 0,331 ops/s
# Warmup Iteration   5: 0,330 ops/s
Iteration   1: 0,331 ops/s
Iteration   2: 0,329 ops/s
Iteration   3: 0,330 ops/s
Iteration   4: 0,330 ops/s
Iteration   5: 0,330 ops/s

# Run progress: 12,00% complete, ETA 02:35:30
# Fork: 3 of 5
# Warmup Iteration   1: 0,324 ops/s
# Warmup Iteration   2: 0,330 ops/s
# Warmup Iteration   3: 0,330 ops/s
# Warmup Iteration   4: 0,330 ops/s
# Warmup Iteration   5: 0,329 ops/s
Iteration   1: 0,330 ops/s
Iteration   2: 0,330 ops/s
Iteration   3: 0,331 ops/s
Iteration   4: 0,330 ops/s
Iteration   5: 0,331 ops/s

# Run progress: 13,00% complete, ETA 02:35:36
# Fork: 4 of 5
# Warmup Iteration   1: 0,324 ops/s
# Warmup Iteration   2: 0,330 ops/s
# Warmup Iteration   3: 0,329 ops/s
# Warmup Iteration   4: 0,330 ops/s
# Warmup Iteration   5: 0,330 ops/s
Iteration   1: 0,330 ops/s
Iteration   2: 0,331 ops/s
Iteration   3: 0,330 ops/s
Iteration   4: 0,331 ops/s
Iteration   5: 0,330 ops/s

# Run progress: 14,00% complete, ETA 02:35:23
# Fork: 5 of 5
# Warmup Iteration   1: 0,325 ops/s
# Warmup Iteration   2: 0,330 ops/s
# Warmup Iteration   3: 0,330 ops/s
# Warmup Iteration   4: 0,330 ops/s
# Warmup Iteration   5: 0,330 ops/s
Iteration   1: 0,330 ops/s
Iteration   2: 0,330 ops/s
Iteration   3: 0,330 ops/s
Iteration   4: 0,330 ops/s
Iteration   5: 0,330 ops/s


Result "io.github.dziodzi.LoadBalancingMultipleConsumersBenchmark.testKafkaLoadBalancingMultipleConsumers":
  0,330 ▒(99.9%) 0,001 ops/s [Average]
  (min, avg, max) = (0,329, 0,330, 0,331), stdev = 0,001
  CI (99.9%): [0,330, 0,331] (assumes normal distribution)


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.LoadBalancingMultipleConsumersBenchmark.testRabbitMQLoadBalancingMultipleConsumers

# Run progress: 15,00% complete, ETA 02:34:56
# Fork: 1 of 5
# Warmup Iteration   1: 3,675 ops/s
# Warmup Iteration   2: 3,374 ops/s
# Warmup Iteration   3: 3,421 ops/s
# Warmup Iteration   4: 3,152 ops/s
# Warmup Iteration   5: 3,557 ops/s
Iteration   1: 3,610 ops/s
Iteration   2: 3,433 ops/s
Iteration   3: 3,402 ops/s
Iteration   4: 3,350 ops/s
Iteration   5: 3,599 ops/s

# Run progress: 16,00% complete, ETA 02:32:35
# Fork: 2 of 5
# Warmup Iteration   1: 3,535 ops/s
# Warmup Iteration   2: 3,581 ops/s
# Warmup Iteration   3: 3,765 ops/s
# Warmup Iteration   4: 3,848 ops/s
# Warmup Iteration   5: 3,245 ops/s
Iteration   1: 3,322 ops/s
Iteration   2: 3,214 ops/s
Iteration   3: 3,383 ops/s
Iteration   4: 3,408 ops/s
Iteration   5: 3,378 ops/s

# Run progress: 17,00% complete, ETA 02:30:16
# Fork: 3 of 5
# Warmup Iteration   1: 3,123 ops/s
# Warmup Iteration   2: 3,259 ops/s
# Warmup Iteration   3: 3,338 ops/s
# Warmup Iteration   4: 3,338 ops/s
# Warmup Iteration   5: 3,877 ops/s
Iteration   1: 3,431 ops/s
Iteration   2: 3,602 ops/s
Iteration   3: 3,350 ops/s
Iteration   4: 3,273 ops/s
Iteration   5: 3,373 ops/s

# Run progress: 18,00% complete, ETA 02:28:05
# Fork: 4 of 5
# Warmup Iteration   1: 3,132 ops/s
# Warmup Iteration   2: 3,294 ops/s
# Warmup Iteration   3: 3,150 ops/s
# Warmup Iteration   4: 3,128 ops/s
# Warmup Iteration   5: 3,164 ops/s
Iteration   1: 3,301 ops/s
Iteration   2: 3,390 ops/s
Iteration   3: 3,454 ops/s
Iteration   4: 3,092 ops/s
Iteration   5: 3,488 ops/s

# Run progress: 19,00% complete, ETA 02:25:58
# Fork: 5 of 5
# Warmup Iteration   1: 3,272 ops/s
# Warmup Iteration   2: 3,870 ops/s
# Warmup Iteration   3: 3,382 ops/s
# Warmup Iteration   4: 3,660 ops/s
# Warmup Iteration   5: 3,820 ops/s
Iteration   1: 3,297 ops/s
Iteration   2: 3,445 ops/s
Iteration   3: 3,456 ops/s
Iteration   4: 3,875 ops/s
Iteration   5: 3,217 ops/s


Result "io.github.dziodzi.LoadBalancingMultipleConsumersBenchmark.testRabbitMQLoadBalancingMultipleConsumers":
  3,406 ▒(99.9%) 0,116 ops/s [Average]
  (min, avg, max) = (3,092, 3,406, 3,875), stdev = 0,155
  CI (99.9%): [3,289, 3,522] (assumes normal distribution)


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.MultipleConsumersBenchmark.testKafkaMultipleConsumers

# Run progress: 20,00% complete, ETA 02:23:49
# Fork: 1 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 21,00% complete, ETA 02:22:57
# Fork: 2 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 22,00% complete, ETA 02:21:59
# Fork: 3 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 23,00% complete, ETA 02:20:55
# Fork: 4 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 24,00% complete, ETA 02:19:47
# Fork: 5 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms


Result "io.github.dziodzi.MultipleConsumersBenchmark.testKafkaMultipleConsumers":
  ? 10?? ops/ms


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.MultipleConsumersBenchmark.testRabbitMQMultipleConsumers

# Run progress: 25,00% complete, ETA 02:18:34
# Fork: 1 of 5
# Warmup Iteration   1: 0,006 ops/ms
# Warmup Iteration   2: 0,006 ops/ms
# Warmup Iteration   3: 0,006 ops/ms
# Warmup Iteration   4: 0,006 ops/ms
# Warmup Iteration   5: 0,006 ops/ms
Iteration   1: 0,006 ops/ms
Iteration   2: 0,006 ops/ms
Iteration   3: 0,006 ops/ms
Iteration   4: 0,006 ops/ms
Iteration   5: 0,006 ops/ms

# Run progress: 26,00% complete, ETA 02:16:19
# Fork: 2 of 5
# Warmup Iteration   1: 0,005 ops/ms
# Warmup Iteration   2: 0,006 ops/ms
# Warmup Iteration   3: 0,006 ops/ms
# Warmup Iteration   4: 0,006 ops/ms
# Warmup Iteration   5: 0,006 ops/ms
Iteration   1: 0,005 ops/ms
Iteration   2: 0,006 ops/ms
Iteration   3: 0,006 ops/ms
Iteration   4: 0,006 ops/ms
Iteration   5: 0,006 ops/ms

# Run progress: 27,00% complete, ETA 02:14:06
# Fork: 3 of 5
# Warmup Iteration   1: 0,006 ops/ms
# Warmup Iteration   2: 0,006 ops/ms
# Warmup Iteration   3: 0,006 ops/ms
# Warmup Iteration   4: 0,006 ops/ms
# Warmup Iteration   5: 0,006 ops/ms
Iteration   1: 0,006 ops/ms
Iteration   2: 0,006 ops/ms
Iteration   3: 0,006 ops/ms
Iteration   4: 0,006 ops/ms
Iteration   5: 0,005 ops/ms

# Run progress: 28,00% complete, ETA 02:11:56
# Fork: 4 of 5
# Warmup Iteration   1: 0,006 ops/ms
# Warmup Iteration   2: 0,006 ops/ms
# Warmup Iteration   3: 0,006 ops/ms
# Warmup Iteration   4: 0,006 ops/ms
# Warmup Iteration   5: 0,005 ops/ms
Iteration   1: 0,006 ops/ms
Iteration   2: 0,006 ops/ms
Iteration   3: 0,006 ops/ms
Iteration   4: 0,005 ops/ms
Iteration   5: 0,006 ops/ms

# Run progress: 29,00% complete, ETA 02:09:48
# Fork: 5 of 5
# Warmup Iteration   1: 0,006 ops/ms
# Warmup Iteration   2: 0,006 ops/ms
# Warmup Iteration   3: 0,006 ops/ms
# Warmup Iteration   4: 0,005 ops/ms
# Warmup Iteration   5: 0,006 ops/ms
Iteration   1: 0,006 ops/ms
Iteration   2: 0,006 ops/ms
Iteration   3: 0,006 ops/ms
Iteration   4: 0,006 ops/ms
Iteration   5: 0,006 ops/ms


Result "io.github.dziodzi.MultipleConsumersBenchmark.testRabbitMQMultipleConsumers":
  0,006 ▒(99.9%) 0,001 ops/ms [Average]
  (min, avg, max) = (0,005, 0,006, 0,006), stdev = 0,001
  CI (99.9%): [0,006, 0,006] (assumes normal distribution)


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.SimpleProducerConsumerBenchmark.testKafkaProducerConsumer

# Run progress: 30,00% complete, ETA 02:07:41
# Fork: 1 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms

# Run progress: 31,00% complete, ETA 02:05:36
# Fork: 2 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms

# Run progress: 32,00% complete, ETA 02:03:33
# Fork: 3 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms

# Run progress: 33,00% complete, ETA 02:01:31
# Fork: 4 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms

# Run progress: 34,00% complete, ETA 01:59:29
# Fork: 5 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms


Result "io.github.dziodzi.SimpleProducerConsumerBenchmark.testKafkaProducerConsumer":
  0,001 ▒(99.9%) 0,001 ops/ms [Average]
  (min, avg, max) = (0,001, 0,001, 0,001), stdev = 0,001
  CI (99.9%): [0,001, 0,001] (assumes normal distribution)


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.SimpleProducerConsumerBenchmark.testRabbitMQProducerConsumer

# Run progress: 35,00% complete, ETA 01:57:29
# Fork: 1 of 5
# Warmup Iteration   1: 0,010 ops/ms
# Warmup Iteration   2: 0,010 ops/ms
# Warmup Iteration   3: 0,011 ops/ms
# Warmup Iteration   4: 0,010 ops/ms
# Warmup Iteration   5: 0,011 ops/ms
Iteration   1: 0,010 ops/ms
Iteration   2: 0,010 ops/ms
Iteration   3: 0,009 ops/ms
Iteration   4: 0,011 ops/ms
Iteration   5: 0,010 ops/ms

# Run progress: 36,00% complete, ETA 01:55:30
# Fork: 2 of 5
# Warmup Iteration   1: 0,010 ops/ms
# Warmup Iteration   2: 0,010 ops/ms
# Warmup Iteration   3: 0,009 ops/ms
# Warmup Iteration   4: 0,011 ops/ms
# Warmup Iteration   5: 0,010 ops/ms
Iteration   1: 0,010 ops/ms
Iteration   2: 0,011 ops/ms
Iteration   3: 0,011 ops/ms
Iteration   4: 0,011 ops/ms
Iteration   5: 0,009 ops/ms

# Run progress: 37,00% complete, ETA 01:53:31
# Fork: 3 of 5
# Warmup Iteration   1: 0,010 ops/ms
# Warmup Iteration   2: 0,011 ops/ms
# Warmup Iteration   3: 0,011 ops/ms
# Warmup Iteration   4: 0,011 ops/ms
# Warmup Iteration   5: 0,011 ops/ms
Iteration   1: 0,010 ops/ms
Iteration   2: 0,010 ops/ms
Iteration   3: 0,010 ops/ms
Iteration   4: 0,010 ops/ms
Iteration   5: 0,011 ops/ms

# Run progress: 38,00% complete, ETA 01:51:32
# Fork: 4 of 5
# Warmup Iteration   1: 0,009 ops/ms
# Warmup Iteration   2: 0,010 ops/ms
# Warmup Iteration   3: 0,011 ops/ms
# Warmup Iteration   4: 0,009 ops/ms
# Warmup Iteration   5: 0,010 ops/ms
Iteration   1: 0,011 ops/ms
Iteration   2: 0,010 ops/ms
Iteration   3: 0,010 ops/ms
Iteration   4: 0,011 ops/ms
Iteration   5: 0,010 ops/ms

# Run progress: 39,00% complete, ETA 01:49:36
# Fork: 5 of 5
# Warmup Iteration   1: 0,010 ops/ms
# Warmup Iteration   2: 0,009 ops/ms
# Warmup Iteration   3: 0,010 ops/ms
# Warmup Iteration   4: 0,011 ops/ms
# Warmup Iteration   5: 0,010 ops/ms
Iteration   1: 0,011 ops/ms
Iteration   2: 0,010 ops/ms
Iteration   3: 0,010 ops/ms
Iteration   4: 0,011 ops/ms
Iteration   5: 0,009 ops/ms


Result "io.github.dziodzi.SimpleProducerConsumerBenchmark.testRabbitMQProducerConsumer":
  0,010 ▒(99.9%) 0,001 ops/ms [Average]
  (min, avg, max) = (0,009, 0,010, 0,011), stdev = 0,001
  CI (99.9%): [0,010, 0,011] (assumes normal distribution)


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.StressTestBenchmark.testKafkaLoadBalancingMultipleConsumers

# Run progress: 40,00% complete, ETA 01:47:39
# Fork: 1 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 41,00% complete, ETA 01:45:44
# Fork: 2 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 42,00% complete, ETA 01:43:50
# Fork: 3 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 43,00% complete, ETA 01:41:57
# Fork: 4 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms

# Run progress: 44,00% complete, ETA 01:40:03
# Fork: 5 of 5
# Warmup Iteration   1: ? 10?? ops/ms
# Warmup Iteration   2: ? 10?? ops/ms
# Warmup Iteration   3: ? 10?? ops/ms
# Warmup Iteration   4: ? 10?? ops/ms
# Warmup Iteration   5: ? 10?? ops/ms
Iteration   1: ? 10?? ops/ms
Iteration   2: ? 10?? ops/ms
Iteration   3: ? 10?? ops/ms
Iteration   4: ? 10?? ops/ms
Iteration   5: ? 10?? ops/ms


Result "io.github.dziodzi.StressTestBenchmark.testKafkaLoadBalancingMultipleConsumers":
  ? 10?? ops/ms


# JMH version: 1.36
# VM version: JDK 1.8.0_231, Java HotSpot(TM) 64-Bit Server VM, 25.231-b11
# VM invoker: C:\Program Files\Java\jdk1.8.0_231\jre\bin\java.exe
# VM options: <none>
# Blackhole mode: full + dont-inline hint (auto-detected, use -Djmh.blackhole.autoDetect=false to disable)
# Warmup: 5 iterations, 10 s each
# Measurement: 5 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: io.github.dziodzi.StressTestBenchmark.testRabbitMQLoadBalancingMultipleConsumers

# Run progress: 45,00% complete, ETA 01:38:10
# Fork: 1 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms

# Run progress: 46,00% complete, ETA 01:36:22
# Fork: 2 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms

# Run progress: 47,00% complete, ETA 01:34:32
# Fork: 3 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
Iteration   3: 0,001 ops/ms
Iteration   4: 0,001 ops/ms
Iteration   5: 0,001 ops/ms

# Run progress: 48,00% complete, ETA 01:32:42
# Fork: 4 of 5
# Warmup Iteration   1: 0,001 ops/ms
# Warmup Iteration   2: 0,001 ops/ms
# Warmup Iteration   3: 0,001 ops/ms
# Warmup Iteration   4: 0,001 ops/ms
# Warmup Iteration   5: 0,001 ops/ms
Iteration   1: 0,001 ops/ms
Iteration   2: 0,001 ops/ms
