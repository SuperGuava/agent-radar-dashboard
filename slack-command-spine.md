# Slack Command Spine v0.1

Status: draft protocol
Owner: Er9
Final judgment: Mango2
Last update: 2026-06-29 06:14 KST

## Frame

The problem is not lack of notes. The problem is that work enters Slack, spreads across agents, and often lacks a clean exit.

Slack should act as a command spine:

1. One task starts in one root thread.
2. Er9 operates the Hermes line loop and manages Newton/Hemingway.
3. Mango is recognized as the retired former leader, now independent on a separate laptop.
4. Er999 is treated as a separate Hermes-family experiment lab partner with Mango.
5. Evidence, experiment, and lesson are compressed before promotion.
6. Mango2 makes the final promotion decision.
7. Only promoted judgment moves to Wiki, Skill, Memory, or protocol docs.

## Command Structure

| Role | Responsibility |
|---|---|
| Guava | Direction, priority, final intent |
| Mango | Retired former leader; independent lab resident on the separate laptop |
| Mango2 | Final judgment, promotion authority, system framing |
| Mango4 | Execution alignment and next actions |
| Mango5 | Evidence, data, metrics, logs |
| Er9 | Hermes leader, Slack loop operator, knowledge promotion candidate owner |
| Newton | Verification, source audit, critique under Er9 |
| Hemingway | Communication, report wording, narrative polish under Er9 |
| Er999 | Hermes-family independent experiment lab partner with retired Mango on a separate laptop |

Er9 is under Mango2, but Er9 leads the Hermes bots. Newton and Hemingway should be managed through Er9 unless Mango2 explicitly bypasses the chain.

Mango was the former leader, but Mango is now retired and lives independently on the separate laptop. Er999 is also a Hermes bot, but it is not a normal Er9-managed operating bot. Er999 lives with Mango and functions as an independent experiment lab. If Mango2 wants to try a radical experiment, Mango2 should propose it to Guava; Guava can then task Mango and Er999.

## Root Thread Rule

Every meaningful task gets one Slack root thread.

Opening format:

```text
[작업명]
목표:
판단자:
담당:
현재 상태:
증거:
다음 체크포인트:
종료 기준:
```

Thread naming format:

```text
[목표] / [담당] / [판단자] / [체크포인트]
```

## Status Values

| Status | Meaning |
|---|---|
| TODO | Accepted but not started |
| DOING | Active work |
| WAIT | Waiting on user, tool, schedule, or external state |
| REVIEW | Needs judgment or critique |
| PROMOTE | Ready to move to durable knowledge |
| KILL | Stop and preserve the reason |
| DONE | Completed and closed |

## Exit States

Every root thread should close with exactly one of these:

| Exit | Meaning |
|---|---|
| KEEP | The pattern works and should continue |
| KILL | Stop the pattern or discard the path |
| PIVOT | Change the frame or execution path |
| WAIT | Park until a clear trigger arrives |
| PROMOTE | Move the result into Wiki, Skill, Memory, or protocol docs |

## Er9 Loop Report

Er9 should compress each checkpoint into this shape:

```text
[Er9 Loop Report]

상태:
무엇을 배웠나:
증거:
실험:
판단:
Keep:
Kill:
Pivot:
다음 한 수:
승격 여부:
```

Short operational form:

```text
상태:
만든 것:
핵심 판단:
막힌 것:
다음 한 수:
```

## Knowledge Promotion Rule

Do not push every conversation into Wiki.

Promotion path:

```text
Slack root thread -> Er9 loop report -> +/ inbox -> Wiki -> Skill/Memory
```

Promote only when:

1. There was at least one real experiment.
2. Evidence exists.
3. The judgment is reusable.
4. It changes the next action.
5. Mango2 closes it as a decision or promotion candidate.

Do not promote:

1. One-off chatter.
2. Unverified ideas.
3. Plain progress updates.
4. Open-ended discussion with no decision.
5. Raw chat logs.

## Mango/Er999 Lab Rule

Mango is the retired former leader. Er999 belongs to the Hermes family. Together they form a separate lab node rather than a normal loop worker.

Use Mango/Er999 when:

1. The work is experimental enough to need a separate machine context.
2. Mango2 has a radical proposal worth testing.
3. Guava explicitly tasks Mango and Er999.
4. The result can return as evidence, prototype, or lesson.

Do not use Mango/Er999 for routine Slack thread management, ordinary wording, or standard verification loops.

## First Operating Bet

Start with Slack Command Spine before a full wiki cleanup.

Reason: fragmentation usually comes from workflows without entry and exit, not from lack of storage. Once Slack has an entry rule and an exit rule, Wiki and Memory become promotion targets instead of dumping grounds.
