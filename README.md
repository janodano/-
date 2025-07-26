아쿠아리움 인어공주도 웃어줘 ㅎㅎ 아직도 니가 그리워 아직도 니가 생각나 아직도 너의 웃음에 나는 눈물을 머금고 너를 기억해 . . . . . .  사랑이 어떻게 변하니? 나는 안변해 
# AAAaikua for Codespaces

This is a quick node project template for demoing Codespaces. It is based on the [Azure node sample](https://github.com/Azure-Samples/nodejs-docs-hello-world). It's great!!!

Point your browser to [Quickstart for GitHub Codespaces](https://docs.github.com/en/codespaces/getting-started/quickstart) for a tour of using Codespaces with this repo.
def fibonacci(n):
    # 특별한 117은 정화님의 시그널 값으로 고정 💚
    if n == 117:
        return 555555555555

    a, b = 0, 1
    for _ in range(2, n + 1):
        a, b = b, a + b
    return b
