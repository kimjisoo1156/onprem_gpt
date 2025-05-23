# 🔒 내부망 전용 ChatGPT 시스템 (Ollama + Llama.cpp 기반)

> 이 프로젝트는 외부 인터넷과 단절된 환경에서 사용할 수 있는 **사내 GPT 챗봇 시스템**입니다.  
> Ollama와 LLaMA.cpp를 활용해 구축되었으며, 민감한 내부 데이터를 안전하게 처리할 수 있습니다.


## 📹 시연 영상

👉 [![Watch the video](https://img.youtube.com/vi/jIQNwkHWayk/0.jpg)](https://www.youtube.com/watch?v=jIQNwkHWayk)


---

## 💡 프로젝트 배경

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="width: 65%; vertical-align: top; padding-right: 40px; line-height: 1.6; font-size: 16px; border: none;">
      회사나 조직 내에서 ChatGPT를 사용하려고 할 때 가장 큰 걸림돌은 <strong>보안 문제</strong>였습니다.<br>
      코드, 문서, 기획 정보 등 민감한 데이터가 외부 서버(OpenAI 등)로 전송될 수 있어,<br>
      <strong>사내 정책상 GPT 사용이 금지되거나 제한</strong>되는 경우가 많았습니다.
    </td>
    <td style="width: 35%; text-align: right; border: none;">
      <img src="https://github.com/user-attachments/assets/3f5f3019-eb62-49be-a4d6-3d9a8b0cc649" width="240"/>
    </td>
  </tr>
</table>



이에 따라, **외부와 단절된 환경에서도 자유롭게 GPT를 활용할 수 있는 시스템**을 만들고자 이 프로젝트를 시작했습니다.

- 인터넷 없이도 로컬에서 작동
- 사내망 내에서만 접근 가능
- 사용자 및 모델 제어 기능 포함
- 추후 내부 문서(RAG) 연동 가능성까지 고려한 구조

보안을 우선으로 하면서도, GPT의 생산성을 그대로 활용할 수 있는  
**온프레미스 GPT 챗봇 시스템**을 목표로 구축하였습니다.


## ✅ 주요 기능

🌐 온프레미스 기반 AI 챗봇


* 외부 인터넷 연결 없이, 로컬 환경에서 완전하게 동작

🧠 LLaMA 기반 자연어 응답


* llama.cpp 엔진을 활용한 고성능 오픈소스 LLM 지원

🔐 로컬 통신 기반 보안 구조


* 모든 요청은 localhost 기준으로 처리되며, 외부 노출 없음

👤 관리자 기능 제공

* 사용자 등록 및 로그인 기능


* 사용자별 모델 접근 제어


* GPT 기능 선택 및 모델 관리


* 대화 기록 조회 

---

## 🏗️ 시스템 구성도
![image](https://github.com/user-attachments/assets/5f771814-3ad0-432d-aad5-f1b961c20b7a)

## 📚 참고 자료
- [Ollama](https://github.com/ollama/ollama?tab=readme-ov-file)  
- [Open WebUI](https://github.com/open-webui/open-webui?tab=readme-ov-file)


