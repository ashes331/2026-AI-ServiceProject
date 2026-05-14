# 2026-AI-ServiceProject
인공지능서비스프로젝트 개인 과제 안내창

<div align="center">

<!-- 보름달 캐릭터 -->
<img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Full%20moon%20face/3D/full_moon_face_3d.png" width="100" alt="잠꾸러기"/>

# 🌕 AI 진로상담소
### feat. 잠꾸러기

**졸면서도 진지하게 들어주는 AI 진로 상담 챗봇**  
*A sleepy but sincere AI career counseling chatbot*

[![Live Demo](https://img.shields.io/badge/🌙_Live_Demo-6d28d9?style=for-the-badge)](https://ashes331.github.io/2026-AI-ServiceProject/)
[![Made with Claude](https://img.shields.io/badge/Made_with-Claude_AI-8b5cf6?style=for-the-badge)](https://claude.ai/new)
[![Powered by Make](https://img.shields.io/badge/Powered_by-Make.com-a78bfa?style=for-the-badge)](https://make.com)

</div>

---

## ✨ 소개 | Introduction

> 잠꾸러기는 낮잠을 좋아하지만, 진로 고민만큼은 진지하게 들어줘요.  
> *Jamkkureogi loves napping, but takes your career concerns seriously.*

**AI 진로상담소**는 Claude AI를 기반으로 한 진로 상담 챗봇 서비스입니다.  
대화를 통해 사용자의 관심사와 강점을 파악하고, 최적의 직업을 추천해드립니다.

**AI Career Counseling** is a career counseling chatbot powered by Claude AI.  
Through conversation, it identifies your interests and strengths to recommend the best career paths.

**아직 한국어만 설정되어있습니다. 영어는 후에 추가가 될 수도 있습니다.**

**Only Korean is set up yet. English may be added later.**

---

## 🚀 주요 기능 | Features

| 기능 | 설명 | Feature | Description |
|------|------|---------|-------------|
| 🌙 **맞춤 상담** | 단계별 대화로 진로를 찾아가요 | **Personalized Counseling** | Step-by-step career discovery |
| 💬 **대화 기억** | 이전 내용을 기억하며 맥락 유지 | **Context Memory** | Remembers conversation history |
| 📊 **결과 저장** | 상담 내용을 Google Sheets에 자동 저장 | **Auto Save** | Saves results to Google Sheets |
| ✨ **직업 추천** | 대화 기반 맞춤 직업 2가지 추천 | **Job Recommendation** | 2 personalized career suggestions |

---

## 💬 상담 흐름 | How It Works

```
🌕 잠꾸러기 인사          →    이름을 알려줘!
   Greeting

👤 이름 입력              →    반가워 [이름]아!
   Enter your name

❓ 관심사 탐색             →    뭘 좋아해? 잘하는 건?
   Explore interests

🎯 진로 방향 파악          →    꿈이 뭐야?
   Identify career goals

✅ 직업 추천              →    [직업1], [직업2] 어때?
   Job recommendations

🔴 상담 종료 버튼 클릭     →    결과 자동 저장
   End session           →    Auto-saved to Sheets
```

---

## 🛠 기술 스택 | Tech Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572b6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![Claude AI](https://img.shields.io/badge/Claude_AI-d97706?style=flat-square)
![Make](https://img.shields.io/badge/Make.com-6d28d9?style=flat-square)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34a853?style=flat-square&logo=googlesheets&logoColor=white)

</div>



```                                                ↗ **Webhook Response**````
**Webhook** → **Anthropic Claude** → **Router**
                                                ↘ **Anthropic Claude** → **Anthropic Claude** → **Google Sheets** → **Webhook Response**   ```
                                                
                                                
---

## 📁 파일 구조 | File Structure

```
📦 프로젝트
 ┣ 📄 index.html        # 챗봇 메인 페이지 | Main chatbot page
 ┗ 📄 README.md         # 프로젝트 안내 | Project guide
```

---

## ⚙️ 사용 방법 | How to Use

**한국어**
1. 사이트에 접속합니다
2. 잠꾸러기의 인사에 이름으로 답해주세요
3. 편하게 진로 고민을 털어놓으세요
4. 대화가 끝나면 **상담 종료** 버튼을 눌러주세요
5. 결과가 자동으로 저장됩니다 ✨

**English**
1. Visit the site
2. Reply with your name to Jamkkureogi's greeting
3. Share your career concerns freely
4. When done, click the **End Session** button
5. Your results are automatically saved ✨

---

## 🌙 디자인 컨셉 | Design Concept

> 밤하늘 아래 잠든 달이 속삭이는 진로 상담  
> *Career counseling whispered by a sleeping moon under the night sky*

- 🎨 **컬러**: 딥 퍼플 + 미드나잇 블랙 + 소프트 화이트
- ✨ **효과**: 반짝이는 별빛 배경 애니메이션
- 🌕 **캐릭터**: 눈 감은 귀여운 보름달 잠꾸러기

---

<div align="center">

**🌕 잠꾸러기가 응원해요!**  
*Jamkkureogi is rooting for you!*

*Made with 💜 & Claude AI*

</div>
