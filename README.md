# Project Intelligence System
  Workflow-based memory system for AI assistants - eliminates context switching

**Problem**: AI assistants lose project **context** every session, making you waste 30 minutes figuring out "what was I working on?"

**Solution**: Workflow-based **memory system** that gives AI assistants actual **project memory**

**Result**: 90% faster project re-entry and context recovery



# Project Intelligence System - ASCII Flowchart

```
                            ┌─────────────────────────────────┐
                            │     📚 REFERENCE_INDEX.md      │
                            │    Master File Index &         │
                            │      Semantic Tags             │
                            └─────────────┬───────────────────┘
                                          │
                          ┌───────────────┼───────────────┐
                          │               │               │
              ┌───────────▼───┐       ┌───▼───┐       ┌───▼────────────┐
              │ ⏭️ NEXT_TASK   │      │ 📊    │       │ 🎯 PRD.md      │
              │     .md        │       │ TASK_ │       │ Project Vision │
              │ Current &      │       │ TRACK │       │ & Goals        │
              │ Next Tasks     │       │ ER.md │       │                │
              └─────┬─────────┘       └───┬───┘       └─────┬──────────┘
                    │                     │                 │
                    │                     │                 │
          ┌─────────▼──┐              ┌───▼────┐        ┌───▼──────────┐
          │ 🚨 ERROR_  │              │ 📈     │        │ 📁 PROJECT_  │
          │ LOGS.md    │              │ PROJ_  │        │ FILES.md     │
          │ Problems & │              │ EVOL.  │        │ Workflow     │
          │ Solutions  │              │ md     │        │ File List    │
          └─────┬──────┘              └───┬────┘        └─────┬────────┘
                │                         │                   │
                │                         │                   │
                └─────────┬───────────────┴─────┬─────────────┘
                          │                     │
                          ▼                     ▼
                 ┌─────────────────────────────────────┐
                 │     🤖👤 AI Assistant /             │
                 │        Human User                   │
                 │   Central Hub for All               │
                 │   Workflow Interactions             │
                 └─────────────┬───────────────────────┘
                               │
            ┌──────────────────┼──────────────────┐
            │                  │                  │
            ▼                  ▼                  ▼
    ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
    │🔍 CONSULTS  │    │✏️ UPDATES   │    │✅ CHECKS    │
    │REFERENCE_   │    │NEXT_TASK &  │    │ALIGNMENT    │
    │INDEX.md     │    │TASK_TRACKER │    │with PRD.md  │
    └─────────────┘    └─────────────┘    └─────────────┘
            
    ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
    │🐛 LOGS      │    │📋 RECORDS   │    │📚 REFERENCES│
    │ISSUES in    │    │CHANGES in   │    │FILES in     │
    │ERROR_LOGS   │    │PROJECT_EVOL │    │PROJECT_FILES│
    └─────────────┘    └─────────────┘    └─────────────┘

═══════════════════════════════════════════════════════════════

                        🎯 WORKFLOW FLOW LOGIC
                        
1. Check NEXT_TASK.md     →  What should I work on?
2. Check TASK_TRACKER.md  →  Where did I leave off?
3. Check PRD.md          →  Does current work align with vision?
4. IF aligned           →  Execute next task
5. IF misaligned        →  Check ERROR_LOGS.md + PROJECT_EVOLUTION.md
6. Understand context   →  Plan → Execute
7. Update relevant files →  Based on what happened

═══════════════════════════════════════════════════════════════

                       📋 CONNECTION TYPES
                       
🔴 Master Control:  REFERENCE_INDEX.md → All Files
🟢 Consultation:   User ↔ REFERENCE_INDEX.md  
🔵 Updates:        User → NEXT_TASK.md & TASK_TRACKER.md
🟠 Alignment:      User ↔ PRD.md
🔴 Error Logging:  User → ERROR_LOGS.md
🟣 Evolution:      User → PROJECT_EVOLUTION.md  
🔷 File Reference: User ↔ PROJECT_FILES.md

═══════════════════════════════════════════════════════════════

                    🌟 PROJECT INTELLIGENCE BENEFITS
                    
✓ Never lose context or forget where you left off
✓ Maintain alignment with project vision at all times  
✓ Track errors and solutions for continuous improvement
✓ Document project evolution and decision history
✓ Enable instant onboarding for new team members
✓ Create AI-ready environment with semantic tagging
✓ Provide structured workflow for human-AI collaboration
```
