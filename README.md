# hadoop-common-2.2.0-bin
hadoop-common-2.2.0/bin
包含winutils.exe
resolve problem： java.io.IOException: Could not locate executable null\bin\winutils.exe in the Hadoop binaries.

如果版本不对，在写入文件中会抛出：java.lang.UnsatisfiedLinkError:org.apache.hadoop.util.NativeCrc32.nativeComputeChunkedSumsByteArray(II[BI[BIILjava/lang/String;JZ)V

# http://blog.csdn.net/lanwenbing/article/details/40783335
