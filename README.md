# PP_Lab_Work

curl -N -X POST "https://api.flaq.ai/api/v1/chat/completions" \
  -H "Authorization: Bearer aaapppp" \
  -H "Accept: text/event-stream" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "qwen-3.8-max-web-search",
    "messages": [
      {
        "role": "user",
        "content": "hii"
      }
    ],
    "stream": true,
    "max_tokens": 2048,
    "top_p": 0.9,
    "top_k": 50
  }'



  my sjj_b0f19e44044ab38cb503d32626a9ccf3
