---
name: Research Interests
about: Configure paper search topics
title: Research Interests
labels: config
assignees: ''
---

```json
{
  "sources": [
    { "type": "arxiv", "name": "arXiv" },
    { "type": "openalex", "name": "OpenAlex" },
    { "type": "crossref", "name": "Crossref" }
  ],
  "conference_sources": {
    "enabled": false,
    "include_default_venues": false,
    "venues": []
  },
  "topics": [
    {
      "id": "risk_aware_uav_inspection",
      "name": "风险感知无人机巡检与路径规划",
      "description": "关注工业环境中的无人机巡检、动态障碍避障、不确定性感知、局部轨迹规划、事件触发重规划、主动感知、目标可见性和安全性评估。",
      "keywords": [
        "UAV inspection",
        "drone inspection",
        "risk-aware path planning",
        "local trajectory planning",
        "dynamic obstacle avoidance",
        "uncertainty-aware planning",
        "event-triggered replanning",
        "active perception",
        "target visibility",
        "moving obstacles",
        "collision avoidance",
        "dynamic window approach"
      ],
      "arxiv_categories": ["cs.RO", "cs.AI", "cs.CV", "eess.SY"]
    },
    {
      "id": "uav_edge_online_learning",
      "name": "无人机边缘计算与在线模型重训练",
      "description": "关注无人机辅助边缘计算、无人机数据采集、边缘智能、在线模型重训练、数据分布漂移、无人机群部署、设备关联、带宽分配和强化学习优化。",
      "keywords": [
        "UAV-enabled edge computing",
        "UAV data collection",
        "mobile edge computing",
        "edge intelligence",
        "online model retraining",
        "continuous learning",
        "data drift",
        "UAV swarm",
        "device association",
        "bandwidth allocation",
        "wireless resource allocation",
        "NOMA",
        "FDMA",
        "reinforcement learning",
        "PPO",
        "mobile edge learning"
      ],
      "arxiv_categories": ["cs.NI", "cs.DC", "cs.LG", "cs.AI", "eess.SY"]
    }
  ]
}
```
