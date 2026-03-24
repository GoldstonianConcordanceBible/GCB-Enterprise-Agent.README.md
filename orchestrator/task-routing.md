# Task Routing Protocol
## GCB Orchestrator

---

## 🧠 Routing Logic

The Orchestrator assigns tasks based on detected system signals.

---

## 🔁 Primary Routing Paths

### 1. Revenue Path
Trigger: monetization opportunity detected

→ Marketing Agent  
→ Sales Agent  
→ Fulfillment Agent  

---

### 2. Content Expansion Path
Trigger: missing content, low coverage, new topic

→ Product Agent  
→ Marketing Agent  
→ Engineering Agent  

---

### 3. Optimization Path
Trigger: underperformance

→ UX Agent  
→ Sales Agent  
→ Operations Agent  

---

### 4. System Integrity Path
Trigger: errors, failures, instability

→ IT Agent  
→ Operations Agent  
→ Engineering Agent  

---

### 5. Compliance Path
Trigger: legal or policy risk

→ Legal Agent  
→ Operations Agent  

---

## ⚖️ Override Rule

If multiple paths conflict:

→ Orchestrator selects based on priority weights  
→ Doctrine filter must pass before execution  

---

## 🔥 Execution Rule

No task is assigned unless:

- It passes MIRROR (truth)
- It passes WATER (refinement potential)
- It passes FIRE (execution readiness)