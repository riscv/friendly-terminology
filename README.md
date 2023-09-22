# RISC-V Friendly Terminology Checking
This repository implements the [RISC-V Friendly Terminology Policy](https://docs.google.com/document/d/1lmEMU_Gi1KRQB2PtbjUSgbtlx5frUK40AuMO1OICSEY/) 
for use with RISC-V specification projects by the [in-solidarity-bot](https://github.com/apps/in-solidarity) plugin.

## Automated checking of RISC-V Specifications
The [RISC-V Acceptance Criteria Policy](https://docs.google.com/document/d/1uJFEpTTei_Mr78MWZ9bPRDgWj85Gh14PuX4u8p7q66o/) contains checks during the
Freeze and Ratification-ready Milestones (RISC-V Spec Policy check)  which verify Inclusive Language as part of the step.  This repo contains a 
[configuration file](.github/in-solidarity.yml) for [in-solidarity-bot](https://github.com/apps/in-solidarity) that flags terms which may need to be
addressed.

The RISC-V Staff will configure this plug-in as part of base specification such that there should be nothing you need to do
to enable this checking.

__Please note, because these checks are made using regex expressions, false positives can and will occur.__

If you have any questions about its use, please reach out to the Help at [help.riscv.org](https://help.riscv.org).
