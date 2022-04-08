# ML-Flow-Exam

## sklearn

```bash
mlflow models serve -m runs:/{RUN_ID}/model --no-conda --port 1234
curl -d '{"columns":["x"], "data":[[1], [-1]]}' -H 'Content-Type: application/json; format=pandas-split' -X POST localhost:1234/invocations
```

## 참고자료

https://blog.naver.com/PostView.nhn?blogId=pjt3591oo&logNo=222298197217&parentCategoryNo=&categoryNo=139&viewDate=&isShowPopularPosts=true&from=search
