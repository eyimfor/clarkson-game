# Clarkson Valuation: Year 1 FCF Master

An interactive educational game for learning the fundamentals of DCF (Discounted Cash Flow) valuation through the Clarkson Lumber Company case.

**Play the Game:** [https://eyimfor.github.io/clarkson-game/](https://eyimfor.github.io/clarkson-game/)

---

## Overview

This interactive game teaches students how to calculate Free Cash Flow (FCF) by walking through the Year 1 (1996) calculations for the Clarkson Lumber Company case step-by-step. It's designed as a supplementary learning tool for corporate finance courses, particularly for students who need additional practice with DCF fundamentals.

### What This Game Covers

This game focuses on **building the foundational skills** needed for DCF valuation:

- Identifying non-operating assets and interest-bearing debt
- Projecting revenues, COGS, and operating expenses
- Calculating EBIT and Net Operating Profit (NOP)
- Computing changes in Net Fixed Assets (ΔNFA)
- Computing changes in Net Operating Working Capital (ΔNOWC)
- Deriving Free Cash Flow from all components
- Understanding why FCF can be negative during growth phases

### What This Game Does NOT Cover

This is intentionally scoped to Year 1 calculations only. A complete DCF valuation requires additional steps not included in this game:

- Projecting FCF for subsequent years (1997-2000)
- Discounting cash flows using WACC
- Calculating terminal value using perpetuity formula
- Computing Enterprise Value
- Final Market Value of Equity calculation

**Pedagogical Note:** By deeply mastering Year 1 calculations, students build the muscle memory and understanding needed to tackle multi-year projections. Once these mechanics become second nature, students can apply them systematically to years 1997-2000 and beyond.

---

## Learning Objectives

After completing this game, students will be able to:

1. **Project operating performance** from revenue through net operating profit
2. **Calculate investment requirements** in both fixed assets and working capital
3. **Derive free cash flow** by combining operating profit and investment needs
4. **Understand the components** that drive FCF (and why growing companies often have negative FCF)
5. **Apply these mechanics** to subsequent years in a full DCF model

---

## Intended Audience

**Primary Users:**
- MBA or undergraduate students in corporate finance courses
- Students working on the Clarkson Lumber Company case
- Students who are behind in class and need structured practice
- Self-learners wanting to understand DCF mechanics

**Prerequisites:**
- Basic understanding of financial statements (Income Statement, Balance Sheet)
- Familiarity with concepts like COGS, EBIT, working capital
- Access to the Clarkson case materials and accompanying "cookbook"

---

## How It Works

The game presents 16 sequential steps, each focusing on a specific calculation:

1. **Interactive Questions:** Students input their answers for each calculation
2. **Immediate Feedback:** Right/wrong answers with explanations
3. **Hints Available:** Students can request hints (reduces cash reward by 50%)
4. **Gamification:** Earn "cash rewards" for correct answers
5. **Progress Tracking:** Visual progress bar and accuracy percentage
6. **Self-Paced Learning:** Take as much time as needed on each step

**Time Commitment:** Approximately 30-45 minutes to complete

---

## Course Integration

### Recommended Use Cases

**1. Supplementary Practice Tool**
- Assign before or after covering the Clarkson case in class
- Use as optional practice for students who want extra help
- Recommend to students who are struggling with DCF concepts

**2. Flipped Classroom**
- Assign as pre-work before discussing the case
- Use class time for higher-level analysis and discussion
- Students come prepared with foundational mechanics mastered

**3. Remedial Learning**
- Identify students who struggled on DCF assignments
- Assign as targeted practice with specific learning outcomes
- Follow up with office hours for remaining questions

**4. Assessment Preparation**
- Students practice before quizzes or exams
- Self-assessment tool to identify weak areas
- Can be completed multiple times for additional practice

### Not Recommended For

- Graded assignments (answers can be found in source code)
- High-stakes assessments
- Replacement for working through the full case
- Standalone learning without the case materials

---

## Security Note

**This is a client-side educational tool.** All answers are stored in the HTML/JavaScript code and can be viewed by students who inspect the source code. This is intentional - the game is designed as a **learning tool, not an assessment tool**.

**Design Philosophy:** Students who choose to "cheat" by looking at the answers only hurt themselves. The real learning comes from working through the calculations. Students who need this tool typically use it honestly because they genuinely want to improve their understanding.

For secure assessments, use Canvas quizzes, proctored exams, or other assessment-specific tools.

---

## Design Choices

### Columbia Business School Branding
- Colors: Columbia blue (#0055a5, #002b5c) with light accents
- Professional, clean interface suitable for business school students
- Mobile-responsive design (though best viewed on laptop/tablet)

### Pedagogical Features
- **Sequential Steps:** Can't skip ahead - ensures mastery of prerequisites
- **Immediate Feedback:** Learn from mistakes right away
- **Hint System:** Scaffolded support without giving away answers
- **Visual Progress:** Motivates completion and shows achievement
- **Negative FCF Explanation:** Addresses common student confusion

---

## Technical Details

**Built With:**
- Pure HTML5, CSS3, and vanilla JavaScript
- No external dependencies or frameworks
- Single-file application (~1,100 lines)
- Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile-responsive (but desktop recommended for best experience)

**Hosting:**
- GitHub Pages (free static site hosting)
- No server-side processing required
- Zero maintenance costs

**Browser Compatibility:**
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Internet Explorer (not supported)

---

## Usage Instructions

### For Students

1. **Access the game:** [https://eyimfor.github.io/clarkson-game/](https://eyimfor.github.io/clarkson-game/)
2. **Read the introduction carefully** to understand the scope
3. **Work through all 16 steps** in order
4. **Use hints strategically** - try to solve first, then use hint if stuck
5. **Focus on understanding** each calculation, not just getting the right answer
6. **Review the final step** to see how Year 1 fits into the complete DCF

**Best Practices:**
- Have the Clarkson case materials and cookbook open while playing
- Work through calculations on paper first, then enter answer
- If you get stuck, review the relevant section of the cookbook
- Play through multiple times if needed - repetition builds mastery

### For Instructors

**Canvas Integration:**
1. Upload to Canvas Files or link to the GitHub Pages URL
2. Create a Page or Assignment with the link
3. Add instructions emphasizing this is for practice, not assessment
4. Recommend time commitment (30-45 minutes)
5. Optional: Request completion screenshot for participation credit

**Framing the Assignment:**
> "This interactive game focuses on Year 1 Free Cash Flow calculations. It's designed to help you master the fundamental building blocks of DCF valuation. This is a learning tool - focus on understanding each step, not just getting a high score. The skills you practice here will serve as the foundation for completing the full Clarkson case and all future DCF valuations."

---

## Updates and Maintenance

**Current Version:** 2.0 (Updated October 2025)
- Clarified Year 1 scope in introduction
- Enhanced Step 16 with complete DCF roadmap
- Updated completion screen with "next steps" guidance
- Improved title to reflect focused scope

**Future Enhancements (Potential):**
- Server-side validation for secure assessment use
- Progress saving across sessions
- Instructor analytics dashboard
- Multi-year version covering 1997-2000
- Terminal value calculation module

---

## License

This educational tool was developed for use in corporate finance courses. Feel free to adapt and use for educational purposes.

---

## About

Created for Columbia Business School  
Course: Corporate Finance  
Case: Clarkson Lumber Company  

For questions or suggestions, please open an issue on GitHub.

---

## Acknowledgments

- Based on the Clarkson Lumber Company case and accompanying valuation cookbook
- Designed for students who need additional support in mastering DCF fundamentals
- Built with feedback from students who were struggling with multi-step calculations

---

**Last Updated:** October 29, 2025
