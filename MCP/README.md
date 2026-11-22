# MCP — `riman-ec-vieton-multi-stick-balm-dropship-cold-start`

## Theme overview

**EN:** RIMAN open-science MCP for INCELLDERM Vieton Multi Stick Balm in Ecuador (B2B Growth & Drop-Shipping). Query n=200 survey CSV, 6-language corpus, and dual DOIs via https://mcp.riman.win/mcp. Mean=3.65/5, Top-2-Box=64.2%.

**ZH:** 力曼 RIMAN 开源 MCP：Ecuador市场 INCELLDERM Vieton Multi Stick Balm（B2B增长与一件代发）。通过 https://mcp.riman.win/mcp 检索 n=200 定量 CSV、六语语料与双基准 DOI。综合均分 3.65/5，Top-2-Box 64.2%。

Interactive report: [https://www.riman.win/www/en/reports/detail/ec-vieton-multi-stick-balm-dropship-cold-start.html](https://www.riman.win/www/en/reports/detail/ec-vieton-multi-stick-balm-dropship-cold-start.html)

## Official remote endpoint
- **MCP (only):** [https://mcp.riman.win/mcp](https://mcp.riman.win/mcp)
- **Repo index:** [https://mcp.riman.win/api/mcp/repos?repo_name=riman-ec-vieton-multi-stick-balm-dropship-cold-start](https://mcp.riman.win/api/mcp/repos?repo_name=riman-ec-vieton-multi-stick-balm-dropship-cold-start)
- **CDN:** [https://cdn.riman.win/repos/riman-ec-vieton-multi-stick-balm-dropship-cold-start/](https://cdn.riman.win/repos/riman-ec-vieton-multi-stick-balm-dropship-cold-start/)
- **GitHub:** [https://github.com/riman-org/riman-ec-vieton-multi-stick-balm-dropship-cold-start](https://github.com/riman-org/riman-ec-vieton-multi-stick-balm-dropship-cold-start)

## Tools
| `list_repos` | Registry tool |
| `get_repo_overview` | Registry tool |
| `query_quantitative_csv` | Registry tool |
| `search_multilingual_corpus` | Registry tool |
| `compare_repos` | Registry tool |
| `list_repo_files` | Registry tool |
| `get_citation` | Registry tool |

## Resources
| URI | Description |
| :--- | :--- |
| `repo://riman-ec-vieton-multi-stick-balm-dropship-cold-start/report` | Full `*_report.json` |
| `repo://riman-ec-vieton-multi-stick-balm-dropship-cold-start/citation` | BibTeX + dual DOIs |

## Local stdio
```bash
pip install mcp
python MCP/server.py
```

## Remote client + bridge
```bash
npx -y mcp-proxy https://mcp.riman.win/mcp
```

```json
{
  "mcpServers": {
    "riman-ec-vieton-multi-stick-balm-dropship-cold-start-mcp": {
      "url": "https://mcp.riman.win/mcp",
      "transport": "http",
      "headers": {},
      "repo_name": "riman-ec-vieton-multi-stick-balm-dropship-cold-start",
      "notes": "Glama / ModelScope hosted endpoint. Pass repo_name=riman-ec-vieton-multi-stick-balm-dropship-cold-start on tool calls. Index: https://mcp.riman.win/api/mcp/repos?repo_name=riman-ec-vieton-multi-stick-balm-dropship-cold-start"
    }
  }
}
```

## Directory listing (Glama / ModelScope)
Use the field-by-field checklist:

→ [`GLAMA_AND_MODELSCOPE_LISTING.md`](./GLAMA_AND_MODELSCOPE_LISTING.md)

- Glama: https://glama.ai/mcp/servers
- ModelScope MCP: https://modelscope.ai/mcp
- ModelScope Skills: https://modelscope.ai/skills (upload `../SKILL/modelscope_skill.zip`)

## Provenance
- Kaggle DOI: [10.34740/kaggle/dsv/22383536](https://doi.org/10.34740/kaggle/dsv/22383536)
- Hugging Face DOI: [10.57967/hf/11688](https://doi.org/10.57967/hf/11688)
- Theme hub: https://www.riman.win/www/en/reports/hub/growth.html
