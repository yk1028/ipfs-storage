# ipfs-storage
> go-ipfs(kubo) library를 기반으로 customizing

## test
- [x] base example
- [x] ipfs node 1개 띄우기 및 file 추가, 조회
- [x] ipfs node 2개 띄워서 swarm connect
- [ ] private network 구성하기
- [ ] peerlist 관리 가능한 형태로 만들기

### issue
- libp2p의 rcmgv.LimitConfig 변경에 따른 kubo library 호환 문제
  - 3/7에 release된 kubo v0.19.0-rc1으로 해결

- kubo library를 활용하여 private network setting 방법
  - Repo에 SwarmKey 활용
