# VEO3 Video Generation Assistant

A comprehensive system prompt and curated example collection for creating professional-quality video generation prompts with Google VEO3. Transform basic ideas into detailed, cinematic prompts that leverage VEO3's full capabilities including audio generation, dialogue, and advanced visual effects.

## 🎯 What This Repository Provides

### 🤖 Ready-to-Use System Prompt
The [`veo3-assistant-system-prompt.md`](veo3-assistant-system-prompt.md) contains a professionally crafted system prompt that transforms any LLM into a VEO3 video generation specialist. This prompt engineering framework enables:

- **Structured 10-Category Planning**: Systematic approach to comprehensive prompt creation
- **Technical Expertise**: Proper camera terminology, composition, and visual effects guidance
- **Audio Integration**: Advanced sound design, dialogue, and music implementation
- **Creative Enhancement**: Narrative depth and visual innovation techniques
- **Quality Assurance**: Built-in checklist and validation protocols

### 📚 Community-Tested Examples
The [`prompt-examples.md`](prompt-examples.md) features an extensive collection of **community-tested prompts published by leading researchers in the field**. These examples demonstrate:

- Progressive prompt refinement techniques
- Complex cinematic scenarios
- Audio and dialogue integration
- Creative applications (LEGO worlds, rap battles, animated conversations)
- Technical demonstrations across all VEO3 categories

## 🚀 Quick Start Guide

### Step 1: Copy the System Prompt
1. Open [`veo3-assistant-system-prompt.md`](veo3-assistant-system-prompt.md)
2. Copy the entire content
3. Paste it as your system prompt in your preferred LLM

### Step 2: Recommended LLM Systems
**Highly Recommended:**
- **Claude Sonnet 4** (Optimal performance and understanding)
- **GPT-4 Turbo/GPT-4o** (Excellent creativity and technical guidance)
- **Gemini Pro** (Strong multimodal understanding)

**Also Compatible:**
- Claude Haiku (for faster responses)
- GPT-3.5 Turbo (basic functionality)
- Any capable instruction-following LLM

### Step 3: Start Creating
Send your basic video idea to the LLM and watch it transform into a detailed, professional VEO3 prompt using the 10-category framework.

## 💡 Example Transformation

**Input:** "A person walking on a beach"

**AI-Enhanced Output:**
```
A cinematic wide shot of a young woman in flowing white linen clothing walking barefoot along a pristine sandy beach at golden hour. The camera performs a slow dolly shot, paralleling her movement as gentle waves lap at the shore. Warm sunset tones of amber and coral illuminate the scene, with soft natural lighting creating a peaceful, contemplative mood. The audio features gentle ocean waves, distant seabird calls, and a subtle ambient instrumental score. Her long hair moves softly in the ocean breeze as she gazes thoughtfully toward the horizon. The color palette emphasizes warm golden and coral sunset tones with cool blue ocean accents. No dialogue, no subtitles.
```

## 📋 The VEO3 10-Category Framework

The system prompt guides through these essential categories:

1. **Scene Description** - Overall narrative and atmosphere
2. **Visual Style** - Artistic direction and genre
3. **Camera Movement** - Technical camera work
4. **Main Subject** - Character and object details
5. **Background Setting** - Environment and location
6. **Lighting/Mood** - Emotional tone and illumination
7. **Audio Cue** - Sound effects and music
8. **Color Palette** - Visual color scheme
9. **Dialogue/Background Noise** - Speech and environmental audio
10. **Subtitles and Language** - Text and cultural context

## 🎬 Key Features

### Advanced Capabilities
- **Audio Integration**: Seamlessly blend music, sound effects, and dialogue
- **Technical Precision**: Professional camera terminology and composition
- **Creative Innovation**: Unexpected element combinations and visual storytelling
- **Progressive Enhancement**: Transform simple ideas into complex scenarios

### Best Practices Built-In
- Detailed prompt construction methodology
- Negative prompting techniques
- Common pitfall avoidance
- Quality assurance protocols

## 📖 Resource Files

### [`veo3-assistant-system-prompt.md`](veo3-assistant-system-prompt.md)
Complete system prompt for LLM implementation. Contains the full framework, technical guides, and interaction protocols. Ready to copy-paste into any compatible LLM system.

**Key Sections:**
- Core capabilities and expertise areas
- 10-category planning framework
- Technical terminology guides
- Audio integration best practices
- Creative enhancement techniques
- User interaction protocols

### [`prompt-examples.md`](prompt-examples.md)
Curated collection of **community-tested prompts from leading VEO3 researchers**. Organized by complexity and category for easy reference and learning.

**Example Categories:**
- Cinematic scene examples
- Progressive refinement demonstrations
- Audio & dialogue integration
- Creative & complex scenarios
- Technical category-specific examples
- Negative prompting techniques

## 🔧 Implementation Examples

### Claude Sonnet 4 Setup
```
System Prompt: [Paste entire content from veo3-assistant-system-prompt.md]

User Message: "Help me create a prompt for a sci-fi chase scene"
```

### API Integration
```python
# Example with OpenAI API
system_prompt = open('veo3-assistant-system-prompt.md', 'r').read()

response = client.chat.completions.create(
    model="gpt-4-turbo",
    messages=[
        {"role": "system", "content": system_prompt},
        {"role": "user", "content": "Create a prompt for a mysterious forest scene"}
    ]
)
```

## 🌟 Why This System Works

### Research-Backed Examples
Our prompt examples come from **leading researchers and practitioners** in the VEO3 community, representing hundreds of hours of testing and refinement.

### Comprehensive Framework
The 10-category system ensures no critical elements are missed, resulting in consistently high-quality video generation.

### LLM-Optimized Design
The system prompt is specifically engineered for optimal LLM performance, with clear instructions, structured frameworks, and built-in quality controls.

## 🤝 Contributing

This repository represents community knowledge. The examples have been curated from publicly shared research and community testing by recognized experts in AI video generation.

## 📄 License

This repository contains curated educational content for VEO3 prompt engineering. Individual prompt examples are attributed to their original research sources.

---

**Ready to create professional VEO3 videos?** Copy the system prompt and start transforming your ideas into cinematic reality.
