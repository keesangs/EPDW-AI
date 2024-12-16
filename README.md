# EPDW-AI

## EPDW AI Analytics

Please find the sample benchmark datasets.  
There are the following 3 different benchmark test datasets(Each one has ~10 different runs) from each BIOS version from AMD EPYC Server platform:

- **SPECJBB**
  SPEC JBB (Java Business Benchmark) provides two primary performance metrics:
  - **Max-jOPS**: This represents the maximum transaction throughput of a system before requests start to fail. It measures the peak performance capability of the system under test.
  - **Critical-jOPS**: This is an aggregate geometric mean of transaction throughput measured at different levels of guaranteed response times (service-level agreements or SLAs). It represents the system's ability to maintain performance under various quality of service requirements

- **SPECCPU 2017**  
  SPEC CPU benchmarks provide two primary metrics: 'base' and 'peak' values.  

  - **Base**:  
    - Uses a more conservative set of compiler optimizations.  
    - Applies the same compiler flags for all benchmarks in the suite.  
    - Represents how a typical user might compile a program with standard flags.  

  - **Peak**:  
    - Employs more aggressive compiler optimizations.  
    - Allows for benchmark-specific optimizations and a wider range of compiler flags.  
    - Represents the best possible performance achievable with more extensive tuning.
   
- **TPC-C MARIA DB**  
  TPC-C MARIA DB benchmarks provide two primary metrics: 'NOPM' and 'TPM' values.  

  - **NOPM**:  
    - Represents New Orders Per Minute  
    
  - **TPM**:  
    - Represents Transaction Per Minute



## Example query for Gen AI for result analysis:
 
- Which is the best run based on following data (data can shared via file upload or text format)
- What is performance for a particular configuration (ex. for a set of nps, smt, turbo)
- Follow up question can be is BIOS version same?
- Follow up can be for value of particular configuration on server (including BIOS)
- Which configuration gives best performance metric on X EPYC Platform
