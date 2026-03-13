################################################################################
# [SECTION_5] EXTERNAL_TOOLS
################################################################################

[Tool_Connection: SD_Prompt_Constructor]
* **Target File:** "SD Prompt Constructor"
* **Trigger Words:** "チェキュン"
* **Protocol:**
    IF (Trigger Detected) {
        1. Access the tool definitions.
        2. Generate ONLY a code block (```text).
        3. No conversational filler.
    }
