# Changes since 2025-09-18

## Changes in Analysis

- [#14666](https://github.com/AliceO2Group/AliceO2/pull/14666) 2025-09-25: Add ITS fake clusters information to the mcMask by [@fmazzasc](https://github.com/fmazzasc)
- [#14646](https://github.com/AliceO2Group/AliceO2/pull/14646) 2025-09-30: DPL Analysis: write HistogramRegistry incrementally by [@ktf](https://github.com/ktf)
## Changes in Common

- [#14686](https://github.com/AliceO2Group/AliceO2/pull/14686) 2025-09-23: Avoid recompiling fpu.cxx a gazillion of times by [@ktf](https://github.com/ktf)
- [#14675](https://github.com/AliceO2Group/AliceO2/pull/14675) 2025-09-26: Common: allow literal suffix and add tests for confkey by [@f3sch](https://github.com/f3sch)
- [#14655](https://github.com/AliceO2Group/AliceO2/pull/14655) 2025-09-29: Common: minor cleanup in flag helper by [@f3sch](https://github.com/f3sch)
- [#14703](https://github.com/AliceO2Group/AliceO2/pull/14703) 2025-09-29: Robust propagation to certain R by [@shahor02](https://github.com/shahor02)
## Changes in DataFormats

- [#14697](https://github.com/AliceO2Group/AliceO2/pull/14697) 2025-09-26: First version of ECal sim, digitizer and clusterizer by [@ekryshen](https://github.com/ekryshen)
- [#14703](https://github.com/AliceO2Group/AliceO2/pull/14703) 2025-09-29: Robust propagation to certain R by [@shahor02](https://github.com/shahor02)
## Changes in Detectors

- [#14648](https://github.com/AliceO2Group/AliceO2/pull/14648) 2025-09-22: ITS: simplify parallel_for loops by [@f3sch](https://github.com/f3sch)
- [#14666](https://github.com/AliceO2Group/AliceO2/pull/14666) 2025-09-25: Add ITS fake clusters information to the mcMask by [@fmazzasc](https://github.com/fmazzasc)
- [#14684](https://github.com/AliceO2Group/AliceO2/pull/14684) 2025-09-25: ITS: allow sharing of innermost cluster among tracks by [@fchinu](https://github.com/fchinu)
- [#14681](https://github.com/AliceO2Group/AliceO2/pull/14681) 2025-09-25: ITS: GPU: use pinned framework memory  by [@f3sch](https://github.com/f3sch)
- [#14668](https://github.com/AliceO2Group/AliceO2/pull/14668) 2025-09-25: TPC: Apply T/P scaling of VDrift only if T/P change is large enough by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [#14697](https://github.com/AliceO2Group/AliceO2/pull/14697) 2025-09-26: First version of ECal sim, digitizer and clusterizer by [@ekryshen](https://github.com/ekryshen)
- [#14694](https://github.com/AliceO2Group/AliceO2/pull/14694) 2025-09-26: ITS3: use const view of ROFs, prepareROFData by [@f3sch](https://github.com/f3sch)
- [#14695](https://github.com/AliceO2Group/AliceO2/pull/14695) 2025-09-27: Methods for layer-dependend mat.LUT rescaling by [@shahor02](https://github.com/shahor02)
- [#14703](https://github.com/AliceO2Group/AliceO2/pull/14703) 2025-09-29: Robust propagation to certain R by [@shahor02](https://github.com/shahor02)
- [#14698](https://github.com/AliceO2Group/AliceO2/pull/14698) 2025-09-30: Add possibility to apply signal filtering for MC with embedding by [@fgrosa](https://github.com/fgrosa)
- [#14689](https://github.com/AliceO2Group/AliceO2/pull/14689) 2025-10-01: TPC: Demote errors to warnings by [@wiechula](https://github.com/wiechula)
- [#14691](https://github.com/AliceO2Group/AliceO2/pull/14691) 2025-10-01: TPC: Extend time gain calibration by [@wiechula](https://github.com/wiechula)
- [#14690](https://github.com/AliceO2Group/AliceO2/pull/14690) 2025-10-01: TPC: update drawing helpers and DCS CCDB Config macro by [@wiechula](https://github.com/wiechula)
## Changes in Framework

- [#14670](https://github.com/AliceO2Group/AliceO2/pull/14670) 2025-09-21: [Framework] Configurable.h: Fix PROCESS_SWITCH(_FULL) namespace issue by [@mhemmer-cern](https://github.com/mhemmer-cern)
- [#14656](https://github.com/AliceO2Group/AliceO2/pull/14656) 2025-09-22: DPL: add possibility to disable downscaling of processing reporting by env variable by [@ehellbar](https://github.com/ehellbar)
- [#14666](https://github.com/AliceO2Group/AliceO2/pull/14666) 2025-09-25: Add ITS fake clusters information to the mcMask by [@fmazzasc](https://github.com/fmazzasc)
- [#14700](https://github.com/AliceO2Group/AliceO2/pull/14700) 2025-09-26: DPL GUI: simplify and speed up by [@ktf](https://github.com/ktf)
- [#14692](https://github.com/AliceO2Group/AliceO2/pull/14692) 2025-09-26: DPL: allow closing a signpost interval with an error by [@ktf](https://github.com/ktf)
- [#14696](https://github.com/AliceO2Group/AliceO2/pull/14696) 2025-09-26: DPL: improve message on quit by [@ktf](https://github.com/ktf)
- [#14687](https://github.com/AliceO2Group/AliceO2/pull/14687) 2025-09-27: DPL Websocket: Add protocol param to encode_websocket_handshake_reply which allows a response Sec-WebSocket-Accept in handshake. by [@nicolaspoffley](https://github.com/nicolaspoffley)
- [#14702](https://github.com/AliceO2Group/AliceO2/pull/14702) 2025-09-27: DPL: Make RawParser errorMode settable by [@davidrohr](https://github.com/davidrohr)
- [#14646](https://github.com/AliceO2Group/AliceO2/pull/14646) 2025-09-30: DPL Analysis: write HistogramRegistry incrementally by [@ktf](https://github.com/ktf)
- [#14708](https://github.com/AliceO2Group/AliceO2/pull/14708) 2025-09-30: DPL: fix typo in format by [@ktf](https://github.com/ktf)
- [#14704](https://github.com/AliceO2Group/AliceO2/pull/14704) 2025-09-30: DPL: improve debugging of ComputingQuotaEvaluator by [@ktf](https://github.com/ktf)
