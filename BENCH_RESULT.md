/Library/Java/JavaVirtualMachines/jdk1.8.0_152.jdk/Contents/Home/bin/java -Dfile.encoding=UTF-8 -cp /Users/cunliu/Downloads/workspaces/git/SortAlgorithms/bin/main com.example.Bench 
### Arrays of length 10
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort |     0.001219ms |     0.000057ms |     0.000057ms |
| Heap sort      |     0.002196ms |     0.002196ms |     0.002185ms |
| Quicksort      |     0.001301ms |     0.001787ms |     0.001895ms |
| Radix sort     |     0.000660ms |     0.000662ms |     0.001063ms |

### Arrays of length 30
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort |     0.013512ms |     0.005607ms |     0.000334ms |
| Heap sort      |     0.018456ms |     0.018996ms |     0.018339ms |
| Quicksort      |     0.010993ms |     0.016241ms |     0.016737ms |
| Radix sort     |     0.002229ms |     0.002209ms |     0.002224ms |

### Arrays of length 100
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort |     0.177864ms |     0.166978ms |     0.003300ms |
| Heap sort      |     0.222130ms |     0.219771ms |     0.219161ms |
| Quicksort      |     0.143128ms |     0.149656ms |     0.202903ms |
| Radix sort     |     0.006664ms |     0.006586ms |     0.009545ms |

### Arrays of length 300
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort |     2.026807ms |     1.422396ms |     0.029221ms |
| Heap sort      |     2.270291ms |     2.229804ms |     2.251331ms |
| Quicksort      |     1.525279ms |     1.563458ms |     2.135574ms |
| Radix sort     |     0.032280ms |     0.031757ms |     0.030825ms |

### Arrays of length 1000
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort |    24.271011ms |    19.223217ms |     0.314028ms |
| Heap sort      |    25.154199ms |    24.295971ms |    23.721790ms |
| Quicksort      |    16.009681ms |    17.157395ms |    22.967851ms |
| Radix sort     |     0.100224ms |     0.099508ms |     0.100140ms |

### Arrays of length 3000
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort |   245.598187ms |   219.677735ms |     2.786471ms |
| Heap sort      |   306.178676ms |   265.160682ms |   257.428912ms |
| Quicksort      |   166.004312ms |   177.076364ms |   241.866617ms |
| Radix sort     |     0.450321ms |     0.451931ms |     0.448796ms |

### Arrays of length 10000
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort |  2842.039870ms |  2775.540136ms |    31.619297ms |
| Heap sort      |  3108.029564ms |  3027.858807ms |  3017.341635ms |
| Quicksort      |  2027.952792ms |  2129.058731ms |  3196.291209ms |
| Radix sort     |     2.484416ms |     1.544434ms |     1.518107ms |

### Arrays of length 30000
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort | 30572.086251ms | 29477.184603ms |   275.176818ms |
| Heap sort      | 32604.552805ms | 32808.561276ms | 31229.617297ms |
| Quicksort      | 21223.204629ms | 23415.942414ms | STACK OVERFLOW |
| Radix sort     |     6.247475ms |     6.048750ms |     6.038161ms |

### Arrays of length 100000
=================================================================
| Algorithm      |         Random |     95% sorted |         Sorted |
| :--            |           ---: |           ---: |           ---: |
| Selection sort | 345706.415734ms | 323030.970940ms |  3057.920117ms |
| Heap sort      | 344404.964876ms | 340565.860511ms | 337897.187937ms |
| Quicksort      | 226663.731675ms | 243063.653600ms | STACK OVERFLOW |
| Radix sort     |    20.650915ms |    19.400566ms |    19.489811ms |