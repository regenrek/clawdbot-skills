---
name: clawdtalk
description: Phone calling and SMS for Clawdbot with deep tool integration for calendar, Jira, web search, and more. Powered by Telnyx.
homepage: https://clawdtalk.com
metadata: {"clawdbot":{"emoji":"📞","requires":{"bins":[]},"install":[]}}
---

# ClawdTalk Skill

Voice AI phone calling and SMS for Clawdbot. Call your AI agent from any phone with deep tool integration.

## Overview

ClawdTalk enables your AI agent to:
- Make and receive phone calls with full voice AI capabilities
- Send and receive SMS messages
- Integrate with Telnyx for reliable telephony
- Access tools: calendar, Jira, web search, and more

## Setup

1. Get Telnyx credentials:
   - Sign up at https://telnyx.com
   - Create an API key
   - Set up a phone number

2. Configure environment variables:
   ```bash
   export TELNYX_API_KEY="your-api-key"
   export TELNYX_PHONE_NUMBER="+1234567890"
   ```

3. Install ClawdTalk:
   ```bash
   git clone https://github.com/team-telnyx/clawdtalk-client.git
   cd clawdtalk-client
   npm install
   ```

## Usage

### Making Calls
Use ClawdTalk to initiate outbound calls with your AI agent.

### Receiving Calls
Configure your Telnyx number to forward to ClawdTalk for inbound calls.

### SMS
Send and receive SMS messages through the ClawdTalk interface.

## Available Tools

ClawdTalk provides access to:
- Calendar management
- Jira integration
- Web search
- And more via tool integration

## Example Prompts

- "Call the customer and discuss their order status"
- "Send an SMS reminder about the meeting"
- "Answer the phone and help the caller with their question"

## Notes

- Powered by Telnyx for reliable telephony
- Voice AI enables natural phone conversations
- Tool integration keeps agents productive during calls