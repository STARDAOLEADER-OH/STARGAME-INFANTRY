# STARGAME-INFANTRY — AI Commanders & Role Replacement

## 🧠 AI Commander System

When no players are available for a leadership role, the system spawns **AI commanders**:

- Follow basic tactical rules
- Can issue basic orders to AI and player soldiers
- Automatically replaced when a qualified player joins

---

## 🔄 Role Inheritance Logic

### Officer Replacement
- If an officer dies or disconnects:
  - A **qualified lower-rank player** may apply to inherit
  - Requires **2/3 approval** from the squad

### Commander Tiers
- **AI Squad Leader** → replaced by player Sergeant+
- **AI Field Officer** → replaced by player Colonel+
- **AI General** → replaced by player Major General (via multi-map vote)

---

## 📥 Open Teams vs. Closed Teams

Commanders choose:
- **Open**: Anyone can join the squad
- **Approval Required**: Commander must approve each new member

---

## ⚖️ Fair Role Rotation

- Active players rotate through officer roles in high-traffic servers
- Overly dominant commanders may be voted out democratically

---