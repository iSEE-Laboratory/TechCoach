# TechCoach
Official repository of AAAI26 paper: TechCoach: Towards Technical Keypoint-Aware Descriptive Action Coaching

## EE4D-DescCoach Dataset
The meta data of EE4D-DescCoach Dataset is constructed in a .json style file:

```
{
    "request-1": {
        "clip_st_ed": [
            Startint time stamp of the instance,
            Ending time stamp of the instance
        ],
        "take_name": "Take name in Ego-Exo4D",
        "take_id": Take id in Ego-Exo4D,
        "task_name": "Task name in Ego-Exo4D",
        "tech_instruction": [
            {
                "body_part": "SPECIFIC_BODY_PART",
                "instruction": "BODY-PART-LEVEL Technical-Point"
            
        ],
        "raw_comment": [
            " ORIGINAL EXPERT COMMENTARY FROM Ego-Exo4D DATASET
        ],
        "response": {
            "regular_dict": [
                {
                    "body_part": "SPECIFIC_BODY_PART",
                    "what_is_done_well": "Technical-Point-level Strength",
                    "what_can_be_improved": "Technical-Point-level Weakness"
                },
                ...
            ],
            "summarization": "Instance-level Commentary on WHAT_IS_DONE_WELL & WHAT_CAN_BE_IMPROVED."
        }
    },
```
