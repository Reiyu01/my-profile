# 鍾昌錦

## 關於我
- **人工智慧**  
- 雜七雜八的外語  
- 機器學習(讓電腦和手機會自己拿筆讀書學習)    

_座右銘：牛奶->優格->起司_

我最喜歡的網站 - [高科大官網](https://www.nkust.edu.tw/)

![這啥?](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExb2cwZmRubnF4bHludWFnbGVlcjIxa3hibW1nd2V5bjRjam5oNnY5cyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/s78TZxnbE7mGQvel6z/giphy.gif)

> ```
> 程式碼之所以有價值
> 是因為它能被閱讀、理解和修改
> 版本控制使這一切成為可能。
> ```


## 教育背景 / 工作經驗
| 學校/公司 | 年份 |
|-----------|------|
| 國立高雄科技大學 | 2023 - 至今 |
| 某學校實驗室 | 2024 - 至今 |

## 程式碼範例
> ```python
> from openai import OpenAI
>
> client = OpenAI()
>
> response = client.chat.completions.create(
>     model="o3-mini",
>     messages=[
>         {"role": "user", "content": "請給我一段呼叫openai的程式碼範例"}
>     ]
> )
>
> print(response.choices[0].message["content"])
> ```
