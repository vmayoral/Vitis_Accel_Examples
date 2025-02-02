Validate Examples
==================================
The main purpose of validate kernels is to test basic HW functionality during bring up of a new platform or hardware board. The bandwidth kernels allow you to measure maximum bandwidth achievable for a given connection.

**Examples Table :**

.. list-table:: 
  :header-rows: 1

  * - **Example**
    - **Description**
    - **Key Concepts/Keywords**
  * - `bandwidth_test <bandwidth_test>`_
    - This Bandwidth Example test the maximum possible bandwidth between Kernel and Global Memory.
    - **Key Concepts**

      * `burst read and write <https://docs.xilinx.com/r/en-US/ug1399-vitis-hls/AXI-Burst-Transfers>`__
      * Bandwidth


  * - `combine_bw_hm <combine_bw_hm>`_
    - This is a simple design that verifies if the platform has basic functionalities It also tests the possible bandwidth between Kernel and Global Memory and validates direct host memory access from kernel.
    - 
  * - `hostmemory_test <hostmemory_test>`_
    - This host memory design explains how direct host memory access can be done by the kernel.
    - **Key Concepts**

      * host memory

      * address translation unit

      **Keywords**

      * XCL_MEM_EXT_HOST_ONLY
      * HOST[0]

  * - `ps_aie_gmio_test <ps_aie_gmio_test>`_
    - This PS AIE kernel tests PS kernel controlling AIE.
    - **Key Concepts**

      * PS Kernel

      * AIE


  * - `ps_bandwidth_test <ps_bandwidth_test>`_
    - This PS validate kernel tests PS kernel functionality.
    - **Key Concepts**

      * PS Kernel


  * - `ps_validate_test <ps_validate_test>`_
    - This PS validate kernel tests PS kernel functionality.
    - **Key Concepts**

      * PS Kernel


  * - `validate_aie_pl <validate_aie_pl>`_
    - Xilinx AIE Validate example
    - 
  * - `validate_embedded <validate_embedded>`_
    - This is a simple design that verifies if the platform has basic functionalities. It also tests the possible bandwidth between Kernel and Global Memory.
    - **Key Concepts**

      * Bandwidth


  * - `verify_test <verify_test>`_
    - This is a simple design to verify that the platform has basic functionality.
    - 

