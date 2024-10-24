# Semantic Color Versioning Cx001

**The only versioning convention that looks as good as it works.**

## The Beauty Behind It

Unlike traditional systems like Semantic Versioning or Date-Based Versioning, **Semantic Color Versioning** uses a sequence of color digits—derived from HEX color codes (e.g., RGBA or RRGGBBAA). These sequences can also be converted to other color formats like RGB, HSV, HSL, etc., offering flexibility while staying visually distinct.

## Parts of a Version

- **Pre-Prefix**:  
  An optional starting character (ASCII or Unicode), which is not part of the main version semantics but serves as a model identifier. This can be any symbol—emoji, glyph, or arbitrary character—purely for aesthetic or branding purposes.

- **Prefix**:  
  The prefix is a single ASCII character marking the beginning of the version sequence. It can be any character except numbers and uppercase/lowercase letters from `F` downwards.

- **Change Number**:  
  Represented by a one or two-character HEX color code (RRGGBB), each segment symbolizes updates:
  - **Red** → Major Update  
  - **Green** → Minor Update  
  - **Blue** → Patch

## Advantages of Semantic Color Versioning

- **Aesthetic Appeal**:  
  This system not only provides clear versioning but also gives each release its unique color identity, making the process visually engaging.
  
- **Motivation**:  
  Imagine eagerly pushing a new major version just to unveil a new color—it’s a fun, fresh incentive to move forward.

- **Consistency**:  
  Aside from the optional pre-prefix, each version has a predictable prefix and a 3- or 6-character HEX sequence, ensuring uniformity.

- **Scalability~ish**:  
  Each color segment offers up to 255 updates—plenty of room for change while keeping things structured.

- **Encouraged Progression**:  
  The system subtly urges you to focus on meaningful updates and move forward. When you max out the color sequence, it might just be a sign to wrap up and move on to new ventures!
