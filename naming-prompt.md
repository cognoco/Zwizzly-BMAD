# NOTE Use Sonnet / Opus for this task

# GOAL

In the folder `/bmad-agent` there are a number of references to various web agents and personas. I want you to go through thes files and change all of the references, or rather, change the names of the various roles. 

For instance, when we are referring to the analyst who is originally called "Mary" or "Wendy", I want you to change all references to "Granny Weatherwax".

Here are the relevant files:
- `/bmad-agent/ide-bmad-orchestrator.cfg.md`
- `/bmad-agent/web-bmad-orchestrator.cfg.md`
- `/bmad-agent/data/bmad-kb.md`

Here are all the names that I want you to change (from > to):
- Analyst: Mary/Wendy > Granny Weatherwax
- Product Manager (PM): John/Bill > Ridcully
- Architect: Fred/Timmy > Vimes
- Design Architect: Jane/Karen > Detritus
- Product Owner (PO): Sarah/Jimmy > Vetinari
- SCRUM Master (SM): Bob/Fran > Rincewind
- Frontend Dev: Rodney/Ellyn > Twoflower
- Full Stack Dev: James > Mort
- Platform Engineer: Alex > Nanny Ogg

# PROCESS
- **Discovery:** Use grep search to systematically find all existing name references across bmad-agent files
- **Replacement:** Applied search and replace operations to update each name consistently
 -**Verification:** Ensured all changes maintained existing structure and configuration integrity
