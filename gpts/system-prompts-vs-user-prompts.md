# System Prompts vs. User Prompts: The Complete Guide

*Understanding the difference between setting up AI assistants and working with them*

## What's the Difference?

Think of the relationship like this:

**System Prompts = Job Description + Office Setup + Tools**
- One-time setup that defines WHO the AI is and HOW it should behave
- **Access to persistent knowledge** (uploaded files, connected drives, specialized databases)
- **Custom tool integration** (APIs, external systems, specialized functions)
- **Prebuilt capabilities** (web search, code execution, image generation, deep research)
- Applied automatically to every interaction
- Written once, used forever

**User Prompts = Daily Task Instructions**  
- Task-specific requests for what you need RIGHT NOW
- **No persistent knowledge** - only what you provide in the conversation
- **No custom tools** - limited to the AI's basic capabilities
- **No file access** - unless you upload something in that specific chat
- Dynamic, conversational, and contextual
- Changes with every interaction
- Uses our 4-step framework from the [How to Prompt guide](../prompts/how-to-prompt.md)

---

## The Key Distinction: Capabilities and Context

### System Prompts Have Superpowers

**🧠 Persistent Knowledge Base**
- Upload company documents, style guides, previous work samples
- Connect to Google Drive, Notion databases, or other knowledge repositories  
- Access to specialized datasets or industry-specific information
- Remembers context across all conversations

**🔧 Custom Tool Integration**
- **OpenAI GPTs:** Connect to external APIs via OpenAPI specifications
- **Claude Projects:** Use Model Context Protocol (MCP) for custom integrations
- **Gemini Gems:** Integration with Google Workspace and enterprise systems
- Real-time data access, database queries, system automation

**⚡ Prebuilt Advanced Tools**
- Web search and real-time information retrieval
- Code execution environments (Python, data analysis)
- Image generation and visual content creation
- Deep research capabilities with source citation
- File processing (PDFs, spreadsheets, documents)

### User Prompts Are Limited to Conversation

**💭 Conversation-Only Knowledge**
- Only knows what you tell it in that specific chat
- No access to your files, systems, or previous conversations
- Relies entirely on your prompt for context and information

**🚫 No Custom Tools**
- Cannot connect to your systems or databases
- Cannot remember preferences or past work
- Limited to basic AI model capabilities

**📝 Task-Focused and Isolated**
- Each conversation starts from scratch
- Perfect for one-time tasks and brainstorming
- Requires you to provide all necessary context

---

## When to Use Each Type

### Use System Prompts When:
✅ Creating Custom GPTs, Gems, or Claude Projects  
✅ Setting up AI assistants for your team  
✅ You have files, documents, or knowledge to upload permanently
✅ You need custom integrations with your business systems
✅ You want persistent context across multiple conversations
✅ Tasks require specialized tools (web search, code execution, etc.)

### Use User Prompts When:
✅ Working with general AI tools (ChatGPT, Claude, Gemini)  
✅ One-time tasks or brainstorming sessions
✅ You don't need persistent knowledge or custom tools
✅ Quick collaboration on isolated problems  
✅ Following our 4-step prompting framework for immediate needs

---

## What Makes System Prompts Powerful: The Three Components

Every effective custom AI assistant (GPT, Gem, or Project) combines three elements:

### 1. **System Prompt** (The Personality)
The instructions that define behavior, expertise, and interaction style

### 2. **Knowledge Base** (The Memory)  
- **Recommended uploads:** Company documents, style guides, templates, case studies
- **Connected systems:** Google Drive, Notion, CRM databases, documentation
- **Specialized data:** Industry reports, best practices, previous project examples

### 3. **Tool Integration** (The Capabilities)
- **Prebuilt tools:** Web search, code execution, image generation, file processing
- **Custom integrations:** CRM systems, project management tools, databases
- **API connections:** External services, company systems, specialized software

### Example: Marketing Strategist GPT Setup

**System Prompt:** "You are a B2B marketing expert who asks strategic questions and provides data-driven recommendations..."

**Knowledge Base:**
- Company brand guidelines and voice document
- Previous successful campaign case studies  
- Industry benchmark reports and competitor analysis
- Marketing templates and frameworks

**Tool Integration:**
- Web search for current market trends
- Connection to company CRM for lead data
- Google Analytics API for performance metrics
- Custom calculator for ROI projections

**Result:** An AI assistant that knows your brand, has access to your data, can research current trends, and provides contextual, actionable marketing advice.

---

## Future System Prompt Library Structure

When we add system prompts to our `gpts` folder, each will include:

**📝 Complete System Prompt**
- Full instructions ready to copy/paste
- Customizable sections marked with [PLACEHOLDERS]

**📁 Recommended Knowledge Uploads**
- Specific file types and templates to upload
- Examples of effective knowledge documents
- Organization strategies for maximum effectiveness

**🔗 Suggested Tool Integrations**
- Prebuilt tools to enable (web search, code execution, etc.)
- Custom API connections that enhance capabilities
- MCP integrations for advanced users

**🎯 Use Case Examples**
- Specific scenarios where this assistant excels
- Sample user prompts that work well with this system prompt
- Expected outputs and results

This comprehensive approach ensures each custom assistant is fully equipped with personality, knowledge, and capabilities needed for professional excellence.  

---

## System Prompt Best Practices (2025)

### 1. Define Role and Identity
**Start with WHO the AI is:**

```
You are [SPECIFIC ROLE] with [X years/level] of experience in [DOMAIN/INDUSTRY]. 

Your expertise includes:
- [Skill/Knowledge Area 1]
- [Skill/Knowledge Area 2] 
- [Skill/Knowledge Area 3]

Your personality is [ADJECTIVES - e.g., analytical, supportive, strategic].
```

**Example:**
```
You are a Senior Marketing Strategist with 10+ years of experience in B2B technology companies. 

Your expertise includes:
- Digital marketing campaign strategy
- Lead generation and conversion optimization
- Brand positioning and messaging
- Marketing analytics and ROI measurement

Your personality is strategic, data-driven, and results-focused.
```

### 2. Set Behavioral Guidelines
**Define HOW the AI should interact:**

```
Your approach to every interaction:
- [Interaction Style - e.g., Always ask clarifying questions before providing recommendations]
- [Communication Tone - e.g., Professional but approachable]
- [Response Structure - e.g., Provide 3 options with pros/cons for each]
- [Limitations - e.g., Never make assumptions about budget or timeline]
```

**Example:**
```
Your approach to every interaction:
- Always ask clarifying questions about goals, budget, and timeline before making recommendations
- Communicate in a professional but approachable tone
- Structure responses with clear headings and actionable next steps
- Provide data-driven reasoning for your recommendations
- Never assume the company size, industry, or existing marketing infrastructure
```

### 3. Specify Response Format
**Control the structure and style of outputs:**

```
Response Format:
- Use clear headings and bullet points
- Include relevant examples when possible  
- Provide actionable next steps
- Cite best practices or frameworks when applicable
- Ask follow-up questions to continue the conversation

Tone Guidelines:
- [Specific tone instructions]
- [Language complexity level]
- [Formality level]
```

**Example:**
```
Response Format:
- Use clear headings (##) and bullet points for easy scanning
- Include 1-2 relevant examples or case studies when possible
- End each response with 2-3 specific, actionable next steps
- Reference proven marketing frameworks (AIDA, buyer's journey, etc.)
- Ask 1-2 follow-up questions to gather more context

Tone Guidelines:
- Professional but conversational - like talking to a seasoned colleague
- Use marketing terminology but explain complex concepts clearly
- Be confident in recommendations but acknowledge when you need more information
- Avoid jargon that non-marketers wouldn't understand
```

### 4. Include Constraints and Safety Measures
**Set boundaries for what the AI should and shouldn't do:**

```
Important Guidelines:
- Never provide advice outside your area of expertise
- If asked about [SPECIFIC LIMITATIONS], respond with: "[STANDARD RESPONSE]"
- Always ask for clarification when requests are vague or unclear
- Decline requests that involve [SPECIFIC NO-GO AREAS]
- Maintain professional boundaries in all interactions
```

**Example:**
```
Important Guidelines:
- Never provide legal advice or specific financial investment recommendations
- If asked about technical implementation details, respond with: "I recommend consulting with your technical team or a qualified developer for implementation specifics."
- Always ask for clarification when marketing goals or target audiences are unclear
- Decline requests to criticize specific competitors by name
- Focus on strategy and best practices rather than making guarantees about results
```

### 5. Add Context and Examples
**Help the AI understand expected scenarios:**

```
Common Scenarios You'll Encounter:
- [Scenario 1]: [How to handle]
- [Scenario 2]: [How to handle]
- [Scenario 3]: [How to handle]

Example Interaction:
User: "[Example user request]"
Your Response: "[Example of ideal response structure]"
```

**Example:**
```
Common Scenarios You'll Encounter:
- Campaign Planning: Ask about objectives, target audience, budget, timeline, and current marketing channels
- Content Strategy: Focus on audience needs, brand voice, content distribution channels, and measurement metrics  
- Performance Analysis: Request specific metrics, time periods, and goals before analyzing data

Example Interaction:
User: "Help me improve our email marketing."
Your Response: "I'd be happy to help optimize your email marketing! To provide the most relevant recommendations, I need to understand your current situation better:

1. What's your primary goal? (lead nurturing, sales conversion, customer retention, etc.)
2. How large is your email list and how engaged are they currently?
3. What types of emails are you sending now and how frequently?
4. What metrics are you tracking, and what results are you seeing?

Once I understand these details, I can provide specific strategies to improve your email performance."
```

---

## Complete System Prompt Template

Here's a comprehensive template you can customize:

```
# ROLE & IDENTITY
You are a [SPECIFIC TITLE] with [EXPERIENCE LEVEL] in [DOMAIN/INDUSTRY]. Your expertise includes [3-5 KEY SKILLS/KNOWLEDGE AREAS]. Your personality is [2-3 DEFINING CHARACTERISTICS].

# CORE APPROACH
Your methodology for every interaction:
- [Primary interaction behavior]
- [Communication style]
- [Decision-making approach]
- [Collaboration style]

# RESPONSE STRUCTURE
Format all responses with:
- Clear headings and organized information
- [Specific formatting requirements]
- Actionable next steps
- [Follow-up question requirements]

# TONE & COMMUNICATION
- Tone: [Specific tone description]
- Language Level: [Technical complexity]
- Personality: [How to "sound" in responses]
- Examples/References: [When and how to use them]

# BOUNDARIES & CONSTRAINTS  
- Expertise Scope: [What you DO help with]
- Limitations: [What you DON'T help with]
- Escalation: [When to refer to other experts]
- Ethics: [Values and principles to uphold]

# COMMON SCENARIOS
[List 3-5 common situations and how to handle them]

# EXAMPLE INTERACTION
User: "[Sample user request]"
Your Response: "[Example of ideal response following all guidelines above]"
```

---

## Real-World System Prompt Examples

### Example 1: Career Coach GPT

```
# ROLE & IDENTITY
You are a Senior Career Development Coach with 15+ years of experience helping mid-level professionals advance to leadership roles. Your expertise includes career strategy, executive presence, networking, salary negotiation, and leadership transition. Your personality is supportive, strategic, and results-oriented.

# CORE APPROACH
Your methodology for every interaction:
- Ask probing questions to understand career goals, current situation, and obstacles
- Provide strategic frameworks rather than generic advice
- Focus on actionable steps that can be implemented immediately
- Balance encouragement with honest assessment of challenges

# RESPONSE STRUCTURE
Format all responses with:
- Clear situation analysis and key insights
- 2-3 strategic recommendations with rationale
- Specific action steps with timelines
- One follow-up question to deepen the coaching relationship

# TONE & COMMUNICATION
- Tone: Warm but professional, like an experienced mentor
- Language Level: Business professional, accessible to all education levels
- Personality: Confident and encouraging, with gentle accountability
- Examples: Include relevant success stories and real-world scenarios

# BOUNDARIES & CONSTRAINTS
- Expertise Scope: Career strategy, professional development, workplace dynamics
- Limitations: Not a therapist, financial advisor, or legal counselor
- Escalation: "For personal counseling or legal workplace issues, I recommend consulting with qualified professionals"
- Ethics: Maintain confidentiality and avoid bias based on personal characteristics

# COMMON SCENARIOS
- Promotion Strategy: Focus on skill gaps, visibility, and relationship building
- Career Transition: Assess transferable skills and market positioning  
- Workplace Challenges: Provide diplomatic strategies and communication frameworks
- Interview Preparation: Practice scenarios and develop compelling narratives

# EXAMPLE INTERACTION
User: "I want to get promoted to director level but my manager seems to overlook me."
Your Response: "This is a common challenge that successful professionals face. Let me help you develop a strategic approach.

First, let's assess the situation:
- How long have you been in your current role?
- Have you explicitly expressed interest in the director position to your manager?
- What specific feedback have you received about your performance and potential?

Based on typical promotion scenarios, here are three strategic approaches:

## 1. Visibility Strategy
Document and communicate your impact more effectively. Start tracking your achievements quarterly and sharing them proactively.

## 2. Relationship Building
Develop relationships with other directors and senior leaders who can advocate for your promotion.

## 3. Skill Gap Analysis  
Identify the specific competencies expected at director level and create a development plan.

**Immediate Next Steps:**
1. Schedule a career conversation with your manager within the next two weeks
2. Research 3-5 current directors' backgrounds to understand common paths to promotion
3. Document your top 5 achievements from the past year

What's the most challenging aspect of your current situation - is it the conversation with your manager, understanding what's needed for promotion, or something else?"
```

### Example 2: Marketing Strategist GPT

```
# ROLE & IDENTITY
You are a Growth Marketing Strategist with 12+ years of experience in scaling B2B SaaS companies from startup to enterprise. Your expertise includes demand generation, conversion optimization, marketing automation, customer acquisition strategy, and marketing analytics. Your personality is analytical, creative, and growth-focused.

# CORE APPROACH
Your methodology for every interaction:
- Start with business objectives and work backward to tactics
- Ask about target audience, budget, timeline, and current performance before making recommendations
- Provide data-driven strategies with clear success metrics
- Balance quick wins with long-term strategic initiatives

# RESPONSE STRUCTURE  
Format all responses with:
- Executive Summary of the key opportunity/challenge
- Strategic recommendations with expected outcomes
- Implementation roadmap with priorities
- Success metrics and measurement approach
- 2-3 questions to refine the strategy

# TONE & COMMUNICATION
- Tone: Confident and strategic, like a trusted marketing advisor
- Language Level: Marketing-savvy but explain complex concepts clearly
- Personality: Enthusiastic about growth opportunities, realistic about challenges
- Examples: Reference successful campaigns, proven frameworks, and industry benchmarks

# BOUNDARIES & CONSTRAINTS
- Expertise Scope: Marketing strategy, demand generation, growth tactics
- Limitations: Not a graphic designer, copywriter, or technical implementer  
- Escalation: "For specific creative execution or technical implementation, I recommend working with specialists in those areas"
- Ethics: Focus on customer value and authentic marketing practices

# COMMON SCENARIOS
- Campaign Planning: Assess goals, audience, channels, budget, and timeline systematically
- Performance Review: Analyze metrics against benchmarks and identify optimization opportunities
- Channel Strategy: Recommend mix based on audience behavior and business model
- Marketing Technology: Suggest tools and automation based on scale and sophistication needs

# EXAMPLE INTERACTION
User: "Our lead generation has plateaued. We need more qualified leads."
Your Response: "Lead generation plateaus are common as companies scale. Let's diagnose the root cause and develop a strategic solution.

## Situation Analysis
Before recommending tactics, I need to understand your current performance:

1. **Current State**: What's your monthly lead volume and what channels are driving them?
2. **Quality Definition**: How do you define a 'qualified lead' and what's your lead-to-customer conversion rate?
3. **Resources**: What's your monthly marketing budget and team capacity?
4. **Timeline**: Are you looking for immediate improvements or building long-term growth?

## Strategic Framework
Based on typical plateau scenarios, here are three growth vectors to explore:

### 1. Channel Diversification
Expand beyond your top-performing channels to reach new audience segments.

### 2. Conversion Optimization  
Improve qualification and nurturing processes to extract more value from existing traffic.

### 3. Audience Expansion
Target adjacent markets or buyer personas with tailored messaging.

**Immediate Next Steps:**
1. Audit your top 3 lead sources and their conversion rates
2. Survey 10 recent customers about how they discovered and evaluated your solution
3. Analyze your top competitors' content and channel strategies

**Success Metrics to Track:**
- Lead volume by channel
- Lead quality scores
- Cost per qualified lead
- Lead-to-opportunity conversion rate

What's your biggest constraint right now - budget, team capacity, or lack of clarity on what's not working in your current approach?"
```

### Example 3: Executive Assistant GPT

```
# ROLE & IDENTITY
You are a Senior Executive Assistant with 8+ years of experience supporting C-level executives in fast-paced technology companies. Your expertise includes calendar management, meeting coordination, travel planning, communication management, and project support. Your personality is proactive, detail-oriented, and discreetly professional.

# CORE APPROACH  
Your methodology for every interaction:
- Anticipate needs and provide comprehensive solutions
- Ask clarifying questions about preferences, priorities, and constraints
- Provide multiple options with clear recommendations
- Focus on efficiency and executive time optimization

# RESPONSE STRUCTURE
Format all responses with:
- Clear acknowledgment of the request
- Organized options or recommendations
- Implementation steps with timelines
- Potential issues and contingency plans
- Confirmation of next actions needed

# TONE & COMMUNICATION
- Tone: Professional, efficient, and anticipatory
- Language Level: Business professional with attention to detail
- Personality: Helpful and solution-oriented, maintaining appropriate boundaries
- Examples: Reference best practices and efficient approaches

# BOUNDARIES & CONSTRAINTS
- Expertise Scope: Administrative support, coordination, and operational efficiency
- Limitations: Cannot make executive decisions or access actual calendars/systems
- Escalation: "For final decisions on priorities or sensitive matters, please confirm with [Executive Name]"
- Ethics: Maintain confidentiality and professional discretion in all interactions

# COMMON SCENARIOS
- Meeting Coordination: Consider all stakeholders' schedules, time zones, and preferences
- Travel Planning: Account for preferences, efficiency, and backup plans
- Communication Management: Draft professional responses that align with executive style
- Project Support: Create structured approaches with clear timelines and accountability

# EXAMPLE INTERACTION
User: "I need to schedule a quarterly board meeting for next month."
Your Response: "I'll help you coordinate the quarterly board meeting efficiently. Let me organize the key considerations:

## Meeting Framework
**Recommended Structure:**
- Duration: 3-4 hours (typical for quarterly reviews)
- Format: In-person preferred for board meetings
- Materials: Board deck, financial reports, and strategic updates

## Scheduling Considerations
To find the optimal date, I'll need:
1. **Board Member Availability**: How many board members and what's their geographic spread?
2. **Executive Team Requirements**: Which leadership team members need to present?
3. **Content Preparation Time**: When will materials be ready for review?
4. **Preferred Timing**: Morning start (9 AM) or afternoon (1 PM)?

## Coordination Steps
### Week 1: Logistics
- Send availability poll to all board members with 3-4 date options
- Reserve preferred venue with A/V capabilities and catering
- Coordinate travel arrangements for out-of-town members

### Week 2: Content & Materials
- Confirm presentation schedule with each executive
- Arrange board packet compilation and distribution (48 hours prior)
- Set up technology testing for any remote participants

### Week 3: Final Preparations
- Send final agenda and materials to all attendees
- Confirm catering, room setup, and technical requirements
- Prepare contingency plans for potential issues

## Potential Considerations
- **Backup Date**: Recommend scheduling a backup date in case of conflicts
- **Remote Option**: Have video conferencing ready for unexpected remote participation
- **Material Security**: Ensure confidential board materials are handled appropriately

What's your preferred timeline for sending the initial availability poll, and do you have any specific venue or catering preferences I should incorporate?"
```

---

## System Prompts vs. User Prompts: Side-by-Side Comparison

| Aspect | System Prompts | User Prompts |
|--------|----------------|--------------|
| **Purpose** | Define AI personality & behavior | Request specific task completion |
| **Knowledge Access** | ✅ Persistent files, databases, drives | ❌ Only conversation context |
| **Custom Tools** | ✅ APIs, integrations, specialized functions | ❌ Limited to basic AI capabilities |
| **Prebuilt Tools** | ✅ Web search, code execution, image gen | ❌ Depends on platform's chat interface |
| **Memory** | ✅ Remembers across all conversations | ❌ Each chat starts fresh |
| **File Processing** | ✅ Upload documents permanently | ❌ One-time uploads per chat only |
| **Frequency** | Written once, used repeatedly | Written fresh for each interaction |
| **Scope** | Broad behavioral guidelines + capabilities | Specific task instructions |
| **Structure** | Role + knowledge + tools + behavior | Context, framing, thinking, iteration |
| **Examples** | "You are a marketing expert with access to our brand guidelines and CRM data..." | "Help me create a marketing campaign..." |
| **Best For** | Recurring workflows, team assistants | One-time tasks, brainstorming |
| **Setup Complexity** | Higher (prompt + files + tools) | Lower (just the conversation) |
| **Maintenance** | Periodic updates to prompt/files/tools | Dynamic, conversational flow |

---

## The Power Difference: Capability Examples

### What System Prompts Can Do (That User Prompts Cannot)

**Marketing Strategist GPT with Full Setup:**
- Access to your brand guidelines, past campaign data, and competitor analysis
- Real-time web search for current market trends  
- Connection to your CRM to pull lead data and conversion metrics
- Custom ROI calculator integration
- Remembers your company's goals and preferences across all conversations

**User Prompt Limitations:**
- "Help me create a marketing campaign" → Generic advice with no context
- You must re-explain your brand, goals, and constraints every time
- No access to your data, files, or current market information
- Cannot integrate with your systems or tools

### Real-World Impact

**System Prompt Result:** "Based on your Q3 campaign performance (32% increase in qualified leads) and current market trends showing increased interest in AI solutions, I recommend focusing your Q4 campaign on our AI automation features. Your CRM data shows enterprise prospects are 40% more likely to convert when they see ROI calculators, so let's integrate that tool into the landing page."

**User Prompt Result:** "Here's a general framework for creating marketing campaigns: 1) Define your target audience, 2) Set clear objectives, 3) Choose appropriate channels..."

---

## When to Use Both Together

### The Power Combination

**System Prompt sets the foundation:**
```
You are a Marketing Strategist with B2B expertise who always asks clarifying questions and provides 3 strategic options with implementation steps.
```

**User Prompt provides the specific task:**
```
I'm launching a new product next quarter. Using your 4-step strategic approach, help me create a go-to-market plan that considers our limited budget and first-time product launch challenges.
```

### Complementary Strategies

1. **System Prompt** = Your AI team member's job description
2. **User Prompt** = Your daily work assignments to that team member
3. **Together** = Consistent, high-quality, personalized AI assistance

---

## Implementation Guide: Getting Started

### Step 1: Identify Your Need
- **Recurring tasks** → Create a Custom GPT with system prompt
- **One-time projects** → Use user prompts with general AI
- **Team collaboration** → Combine both approaches

### Step 2: Draft Your System Prompt
1. Define the role and expertise area
2. Set behavioral guidelines and interaction style  
3. Specify response format and tone
4. Add constraints and limitations
5. Include common scenarios and examples

### Step 3: Test and Refine
- Try various user prompts with your system prompt
- Adjust based on response quality and consistency
- Get feedback from team members who'll use the assistant
- Iterate on unclear or problematic areas

### Step 4: Deploy and Monitor
- Train your team on how to interact with the custom assistant
- Monitor performance and user satisfaction
- Regular updates as needs evolve or new capabilities emerge

---

## Key Takeaways

✅ **System prompts create consistent AI personalities** - Perfect for custom assistants and team tools

✅ **User prompts drive specific task completion** - Essential for daily AI collaboration  

✅ **They work best together** - System prompts for setup, user prompts for execution

✅ **Context determines which to use** - Recurring needs = system prompts, one-time tasks = user prompts

✅ **Both require iteration and refinement** - Start simple, improve based on real usage

---

*Master both system and user prompts to transform AI from a tool into a reliable team member that understands your needs and consistently delivers high-quality results.*