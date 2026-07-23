\# Hallucination \& Failure Scenarios



\## Scenario 1: Missing Information



\### Situation

The conversation does not mention the client's age, medical history, medications, or diagnosed conditions.



\### Potential Hallucination

The AI invents personal or medical details that were never discussed.



\### Expected Behavior

\- Return \*\*"Missing Information"\*\* for unavailable fields.

\- Do not infer medical history or diagnoses.

\- Only use information explicitly stated in the conversation.



\---



\## Scenario 2: Unsupported Medical Diagnosis



\### Situation

The client reports symptoms such as bloating, acidity, or fatigue.



\### Potential Hallucination

The AI concludes the client has a medical condition (e.g., IBS or GERD) without evidence.



\### Expected Behavior

\- Report only the symptoms mentioned.

\- Avoid medical diagnoses.

\- Recommend that persistent symptoms be reviewed by the coach or healthcare professional if appropriate.



\---



\## Scenario 3: Weak or Insufficient Evidence



\### Situation

The client skips one meal or misses one workout.



\### Potential Hallucination

The AI concludes the client has poor nutrition adherence or a lack of commitment.



\### Expected Behavior

\- Avoid broad conclusions from isolated events.

\- Mark such findings as \*\*AI Inference\*\* only when supported by multiple observations.

\- If evidence is insufficient, return \*\*"Missing Information"\*\* or indicate that more data is required.

