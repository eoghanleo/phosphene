ID: IDEA-0001
IssueNumber: 1
Title: RAG assistant for electricians accessing AS3000 wiring rules
Status: Draft
Updated: 2026-02-05
Dependencies: 

```text
[V-SCRIPT]:
create_idea.sh
ideation_storm_table_bootstrap.sh
provide_next_storm_prompt.sh
ideation_storm_set_description.sh
```

## Problem / opportunity

- Electricians frequently need to reference AS/NZS 3000 (Wiring Rules) and related standards during jobs
- The AS3000 PDF is dense, poorly searchable, and awkward to navigate on mobile devices on-site
- Finding the specific clause that applies to a situation (e.g., cable sizing for a specific load, clearance requirements) takes time and expertise
- Mistakes due to misinterpreting or missing a rule can result in failed inspections, rework, or safety hazards

## Target user hypotheses

- Licensed electricians (journeymen and masters) in Australia/NZ who do residential and commercial work
- Apprentices studying for licensing exams who need quick reference during study
- Electrical inspectors who need to verify compliance against specific clauses
- Small electrical contractors who can't afford dedicated compliance staff

## Next research questions

- How often do electricians actually reference AS3000 during a typical week/job?
- What are the most common lookup scenarios (cable sizing, earthing, clearances, RCD requirements)?
- What do they currently use? (Physical book, PDF on tablet, Google, asking colleagues?)
- What would they pay for a tool that gives instant, accurate answers with clause references?
- Are there liability/trust concerns with AI-generated compliance advice?
- What adjacent standards matter? (AS3008 cable selection, AS3018 switchboards, state-specific amendments)

## Storm table

| STORM-ID | PROBE_1 | PROBE_2 | RING | DESCRIPTION |
| --- | --- | --- | --- | --- |
| STORM-0001 | CM-000315:IMPCOVETOUSNESS | CM-000221:DREAMER | adjacent | <Description> |
| STORM-0002 | CM-000315:IMPCOVETOUSNESS | CM-000221:DREAMER | orthogonal | <Description> |
| STORM-0003 | CM-000315:IMPCOVETOUSNESS | CM-000221:DREAMER | extrapolatory | <Description> |
| STORM-0004 | CM-000315:IMPCOVETOUSNESS | CM-000539:CAMOUFLAGE | adjacent | <Description> |
| STORM-0005 | CM-000315:IMPCOVETOUSNESS | CM-000539:CAMOUFLAGE | orthogonal | <Description> |
| STORM-0006 | CM-000315:IMPCOVETOUSNESS | CM-000539:CAMOUFLAGE | extrapolatory | <Description> |
| STORM-0007 | CM-000315:IMPCOVETOUSNESS | CM-000169:BERG | adjacent | <Description> |
| STORM-0008 | CM-000315:IMPCOVETOUSNESS | CM-000169:BERG | orthogonal | <Description> |
| STORM-0009 | CM-000315:IMPCOVETOUSNESS | CM-000169:BERG | extrapolatory | <Description> |
| STORM-0010 | CM-000315:IMPCOVETOUSNESS | CM-000930:BONFIRESPARKS | adjacent | <Description> |
| STORM-0011 | CM-000315:IMPCOVETOUSNESS | CM-000930:BONFIRESPARKS | orthogonal | <Description> |
| STORM-0012 | CM-000315:IMPCOVETOUSNESS | CM-000930:BONFIRESPARKS | extrapolatory | <Description> |
| STORM-0013 | CM-000221:DREAMER | CM-000539:CAMOUFLAGE | adjacent | <Description> |
| STORM-0014 | CM-000221:DREAMER | CM-000539:CAMOUFLAGE | orthogonal | <Description> |
| STORM-0015 | CM-000221:DREAMER | CM-000539:CAMOUFLAGE | extrapolatory | <Description> |
| STORM-0016 | CM-000221:DREAMER | CM-000169:BERG | adjacent | <Description> |
| STORM-0017 | CM-000221:DREAMER | CM-000169:BERG | orthogonal | <Description> |
| STORM-0018 | CM-000221:DREAMER | CM-000169:BERG | extrapolatory | <Description> |
| STORM-0019 | CM-000221:DREAMER | CM-000930:BONFIRESPARKS | adjacent | <Description> |
| STORM-0020 | CM-000221:DREAMER | CM-000930:BONFIRESPARKS | orthogonal | <Description> |
| STORM-0021 | CM-000221:DREAMER | CM-000930:BONFIRESPARKS | extrapolatory | <Description> |
| STORM-0022 | CM-000539:CAMOUFLAGE | CM-000169:BERG | adjacent | <Description> |
| STORM-0023 | CM-000539:CAMOUFLAGE | CM-000169:BERG | orthogonal | <Description> |
| STORM-0024 | CM-000539:CAMOUFLAGE | CM-000169:BERG | extrapolatory | <Description> |
| STORM-0025 | CM-000539:CAMOUFLAGE | CM-000930:BONFIRESPARKS | adjacent | <Description> |
| STORM-0026 | CM-000539:CAMOUFLAGE | CM-000930:BONFIRESPARKS | orthogonal | <Description> |
| STORM-0027 | CM-000539:CAMOUFLAGE | CM-000930:BONFIRESPARKS | extrapolatory | <Description> |
| STORM-0028 | CM-000169:BERG | CM-000930:BONFIRESPARKS | adjacent | <Description> |
| STORM-0029 | CM-000169:BERG | CM-000930:BONFIRESPARKS | orthogonal | <Description> |
| STORM-0030 | CM-000169:BERG | CM-000930:BONFIRESPARKS | extrapolatory | <Description> |
## Revision passes

- Builder: <coherence pass notes>
- Critic: <gaps/contradictions found and fixed>

## Notes

- AS/NZS 3000:2018 is the current edition (~300 pages of dense technical content)
- Standards are copyrighted by Standards Australia - licensing/distribution is a consideration
- Similar pain exists for other trades (plumbers with AS3500, builders with NCC/BCA)
- Potential expansion to other electrical standards (AS3008, AS3018, AS4777 for solar)
