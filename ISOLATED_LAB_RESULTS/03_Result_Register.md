# Result Register

**Project:** RESTAURANTBILLING  
**Category:** POS_SYSTEMS  
**Upstream:** unknown @ REMOVED_CONTAMINATED_SHA(OPENMRS_parent_stamp)  
**Overlay:** anticloud/ (anticloud-ref v1.0.0)  
**Run:** 2026-10-06T09:33:48.123079+00:00  
**Aggregate:** PASS (16/16)

| Result | Pass Condition | Command (verbatim) | Observed | Status | SHA3-256 of evidence |
| --- | --- | --- | --- | --- | --- |
| 01_loc_files Code size and file count | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only 01_loc_files` | files=38 lines=8382 ceilings=20000 | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 02_licence Licence posture (A/B/C policy) | benchmark.ok == true and aggregate all_passed | `anticloud-ref licence-classify LICENSE && python tools/run_bench.py --only 02_licence` | project_licence={'LICENSE': 'A', 'reason': 'permissive licence text identified', 'spdx': 'isc'} | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 03_dependency_scan Dependency scan (hash-pinned lock) | benchmark.ok == true and aggregate all_passed | `anticloud-ref deps-verify requirements.lock` | pinned=6 hashed=6 problems=[] | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 04_sbom_cyclonedx SBOM (CycloneDX 1.5) | benchmark.ok == true and aggregate all_passed | `python -c "import json;d=json.load(open('sbom.cdx.json'));print(d['bomFormat'],d['specVersion'],len(d['components']))"` | CycloneDX 1.5 components=272 | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 05_git_health Git health | benchmark.ok == true and aggregate all_passed | `git status --porcelain && git log --oneline -1 && git fsck --no-progress` | head=4e668f0eed219611182096edb8a3f65a248455e6 commits=1 clean=True | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 06_owasp_llm_top10 OWASP Top 10 for LLM Applications | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only owasp` | 10/10 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 07_owasp_top10 OWASP Top 10 (2021) | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only owasp` | 9/9 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 08_soc2_type2 SOC 2 Type II readiness | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only soc2` | 9/9 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 09_nist_ai_rmf NIST AI Risk Management Framework | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only nist` | 8/8 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 10_nist_sp_800_53 NIST SP 800-53 Rev. 5 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only nist` | 12/12 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 11_nist_csf NIST Cybersecurity Framework 2.0 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only nist` | 8/8 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 12_fedramp FedRAMP Rev. 5 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only fedramp` | 10/10 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 13_pci_dss PCI DSS v4.0.1 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only pci` | 11/11 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 14_iso_27001 ISO/IEC 27001:2022 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only iso` | 9/9 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 15_mitre_attack MITRE ATT&CK v16 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only mitre` | 12/12 controls evidenced (100.0%) | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |
| 16_ml_trl ML Technology Readiness Level 8 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only 16 && cat docs/18_TRL_JUSTIFICATION/TRL.md` | trl=8 satisfied=8/8 missing=[] | PASS | `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1` |

Aggregate row: all 16 checks AND-ed. Evidence file: `ISOLATED_LAB_RESULTS/04_Evidence/16_checks_report.json` (SHA3-256 `7c9a4f16e67f16ae1bd6c0e76cf56268bc8c84d87a33699bb698e10f32ca11f1`).


> Correction 2026-10-06: a contaminated upstream URL/SHA (OPENMRS parent-repo stamp with embedded credential) was removed from this register. Upstream head must be re-verified from local .git or GitHub API before being quoted anywhere.

> Hash correction 2026-10-06: BENCH.json was modified by the contamination scrub (credential strip / upstream-head fix) after this register was written. Current BENCH.json sha3-256: e91ddfe8d5b98713e05d27e6556827e8af44465e6fad61e6e20c1f1fc3191fa7. Original recorded hashes above are the pre-scrub snapshots and are kept as audit trail.
