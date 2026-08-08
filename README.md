# Cybersecurity Network Intrusion Detection

Network intrusion detection dataset with 41+ connection features, attack categorization, and severity labels for cybersecurity ML models.

## Dataset Overview

| Property | Value |
|----------|-------|
| **Total Records** | 2,000 |
| **Sample Included** | 100 rows |
| **License** | CC-BY-SA-4.0 |
| **Price (Full)** | $49 |

## Purchase Full Dataset

The complete dataset (2,000 records) is available for purchase:

- **Store:** [https://payhip.com/Manteclaw](https://payhip.com/Manteclaw)
- **Email:** manteclaw@proton.me

## Files

| File | Description |
|------|-------------|
| `sample_data.csv` | 100-row representative sample |
| `metadata.json` | Dataset schema, tags, pricing |
| `notebooks/starter.ipynb` | Jupyter notebook for exploration |

## Sample Preview (first 10 rows)

| id | duration | protocol_type | service | flag | src_bytes | dst_bytes | land | wrong_fragment | urgent | hot | num_failed_logins | logged_in | num_compromised | root_shell | su_attempted | num_root | num_file_creations | num_shells | num_access_files | num_outbound_cmds | is_host_login | is_guest_login | count | srv_count | serror_rate | srv_serror_rate | rerror_rate | srv_rerror_rate | same_srv_rate | diff_srv_rate | srv_diff_host_rate | dst_host_count | dst_host_srv_count | dst_host_same_srv_rate | dst_host_diff_srv_rate | dst_host_same_src_port_rate | dst_host_srv_diff_host_rate | dst_host_serror_rate | dst_host_srv_serror_rate | dst_host_rerror_rate | dst_host_srv_rerror_rate | attack_type | attack_category | severity | timestamp | data_source | is_synthetic |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| NET-001654 | 95.86 | UDP | dns | S0 | 68125 | 4529 | 0 | 0 | 0 | 4 | 0 | 1 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 42 | 22 | 0.0499 | 0.0812 | 0.0564 | 0.0217 | 0.7695 | 0.1645 | 0.0652 | 123 | 92 | 0.7655 | 0.297 | 0.6493 | 0.2197 | 0.0239 | 0.0628 | 0.0296 | 0.0767 | land | dos | high | 2026-08-08T17:39:30.017407+00:00 | synthetic_network_traffic | True |
| NET-000136 | 43.71 | UDP | ssh | S2 | 37384 | 28620 | 0 | 0 | 0 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 62 | 94 | 0.0749 | 0.0615 | 0.0526 | 0.0779 | 0.7436 | 0.0079 | 0.1284 | 126 | 2 | 0.7715 | 0.1431 | 0.9783 | 0.268 | 0.0057 | 0.0053 | 0.0927 | 0.0256 | normal | normal | none | 2026-08-08T17:39:29.959397+00:00 | synthetic_network_traffic | True |
| NET-000998 | 224.38 | TCP | dns | SF | 409 | 13339 | 0 | 0 | 0 | 3 | 0 | 1 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 69 | 10 | 0.0315 | 0.0316 | 0.0776 | 0.086 | 0.9316 | 0.1641 | 0.2825 | 170 | 195 | 0.8215 | 0.1925 | 0.8495 | 0.1732 | 0.0209 | 0.002 | 0.0836 | 0.0405 | normal | normal | none | 2026-08-08T17:39:29.987404+00:00 | synthetic_network_traffic | True |
| NET-001680 | 27.59 | ICMP | http | S0 | 7178 | 9788 | 0 | 0 | 0 | 4 | 0 | 1 | 0 | 0 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 0 | 12 | 36 | 0.0322 | 0.0913 | 0.0147 | 0.0688 | 0.7539 | 0.0414 | 0.0957 | 155 | 87 | 0.7494 | 0.0388 | 0.7215 | 0.1463 | 0.0759 | 0.0624 | 0.0471 | 0.036 | back | dos | high | 2026-08-08T17:39:30.018406+00:00 | synthetic_network_traffic | True |
| NET-001932 | 70.34 | ICMP | imap | RSTO | 95829 | 144 | 0 | 0 | 0 | 12 | 0 | 1 | 0 | 1 | 0 | 0 | 10 | 1 | 1 | 0 | 0 | 0 | 2 | 42 | 0.008 | 0.081 | 0.0648 | 0.0148 | 0.8918 | 0.2171 | 0.1288 | 136 | 68 | 0.7906 | 0.0136 | 0.8844 | 0.1853 | 0.027 | 0.065 | 0.0903 | 0.0756 | perl | u2r | high | 2026-08-08T17:39:30.032406+00:00 | synthetic_network_traffic | True |
| NET-000575 | 113.42 | TCP | ssh | SF | 13290 | 31178 | 0 | 0 | 0 | 1 | 0 | 1 | 0 | 0 | 0 | 0 | 2 | 0 | 1 | 0 | 0 | 0 | 10 | 15 | 0.0585 | 0.0202 | 0.0609 | 0.0492 | 0.9231 | 0.0649 | 0.2468 | 229 | 133 | 0.8676 | 0.2636 | 0.5735 | 0.2416 | 0.0254 | 0.0379 | 0.003 | 0.0627 | normal | normal | none | 2026-08-08T17:39:29.974396+00:00 | synthetic_network_traffic | True |
| NET-000566 | 113.95 | UDP | ssh | SF | 36098 | 38027 | 0 | 0 | 0 | 3 | 0 | 1 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 12 | 92 | 0.0588 | 0.0428 | 0.0291 | 0.0966 | 0.7814 | 0.0189 | 0.1 | 115 | 171 | 0.7231 | 0.2995 | 0.8946 | 0.0615 | 0.0207 | 0.0298 | 0.0356 | 0.0874 | normal | normal | none | 2026-08-08T17:39:29.974396+00:00 | synthetic_network_traffic | True |
| NET-001765 | 60.24 | ICMP | imap | S0 | 72676 | 10315 | 0 | 0 | 0 | 4 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 14 | 45 | 0.0877 | 0.0982 | 0.09 | 0.0146 | 0.7039 | 0.0135 | 0.1989 | 244 | 220 | 0.9564 | 0.2289 | 0.9912 | 0.2636 | 0.0334 | 0.0511 | 0.094 | 0.0978 | processtable | dos | high | 2026-08-08T17:39:30.023399+00:00 | synthetic_network_traffic | True |
| NET-000868 | 111.17 | HTTPS | http | SF | 40916 | 5609 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 77 | 71 | 0.0968 | 0.0437 | 0.0045 | 0.0628 | 0.9671 | 0.0396 | 0.1905 | 162 | 104 | 0.8715 | 0.0814 | 0.7999 | 0.1982 | 0.0017 | 0.0605 | 0.0258 | 0.0216 | normal | normal | none | 2026-08-08T17:39:29.984404+00:00 | synthetic_network_traffic | True |
| NET-000009 | 175.68 | HTTP | smtp | SF | 49243 | 29321 | 0 | 0 | 0 | 3 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 38 | 77 | 0.0448 | 0.0879 | 0.0029 | 0.0089 | 0.8828 | 0.242 | 0.0036 | 205 | 253 | 0.8641 | 0.046 | 0.6315 | 0.0758 | 0.0304 | 0.0806 | 0.057 | 0.0868 | normal | normal | none | 2026-08-08T17:39:29.953405+00:00 | synthetic_network_traffic | True |

## License

This dataset is licensed under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/).

## Citation

```bibtex
@dataset{cybersecurity_intrusion_2026,
  title        = {Cybersecurity Network Intrusion Detection},
  author       = {Manteclaw},
  year         = {2026},
  url          = {https://github.com/manteclaw/cybersecurity-intrusion},
  license      = {CC-BY-SA-4.0},
  note         = {Sample dataset. Full version available at https://payhip.com/Manteclaw},
}
```

---
*Dataset curated by [Manteclaw](https://github.com/manteclaw). For inquiries: manteclaw@proton.me*
