``` ini

BenchmarkDotNet=v0.12.1, OS=Windows 10.0.19042
Intel Core i7-8750H CPU 2.20GHz (Coffee Lake), 1 CPU, 12 logical and 6 physical cores
.NET Core SDK=5.0.201
  [Host]     : .NET Core 3.1.13 (CoreCLR 4.700.21.11102, CoreFX 4.700.21.11602), X64 RyuJIT
  DefaultJob : .NET Core 3.1.13 (CoreCLR 4.700.21.11102, CoreFX 4.700.21.11602), X64 RyuJIT


```
|  Method | nodes | nrows |     Mean |    Error |   StdDev |   Median |
|-------- |------ |------ |---------:|---------:|---------:|---------:|
| **compute** |     **1** |    **10** | **584.5 ms** | **14.64 ms** | **42.02 ms** | **572.4 ms** |
| **compute** |     **1** |    **15** | **593.4 ms** | **11.80 ms** | **32.70 ms** | **586.8 ms** |
| **compute** |     **5** |    **10** | **539.0 ms** | **10.78 ms** | **26.84 ms** | **532.7 ms** |
| **compute** |     **5** |    **15** | **560.9 ms** | **10.91 ms** | **12.13 ms** | **563.0 ms** |
