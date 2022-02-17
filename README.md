# workflow

1. 커밋에 [WARNING] 메세지 추가 후 푸쉬
2. develop -> master PR 생성
3. https://github.com/marketplace/actions/gs-commit-message-checker 가 [WARNING] 감지하고 pr에 comment 남김
4. https://github.com/Khan/pull-request-comment-trigger 가 pr comment 확인 후 merge or cancel 메세지 emoji 남김
5. emoji 클릭
