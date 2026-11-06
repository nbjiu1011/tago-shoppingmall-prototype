# tago-shoppingmall-prototype

tagoplus 쇼핑몰 **전체 기획서 겸 HTML 프로토타입**입니다.
각 파일은 단일 HTML로, 서버·빌드 없이 브라우저에서 바로 실행됩니다.

## 구성
| 파일 | 화면 | 설명 |
|------|------|------|
| `index.html` | 플랫폼 관리자 + 판매자센터 | 입점형 기준. 플랫폼 12개 대메뉴 50개 화면, 판매자센터 15개 화면. 프로필 메뉴에서 역할별 권한 전환 |
| `shop.html` | 사용자(Storefront) | 입점형 기준. 홈·카테고리·상품상세·판매자 페이지·장바구니·주문·로그인·회원가입·마이페이지·고객센터 |
| `standalone/index.html` | 독립몰 관리자 | 고객사 한 곳이 자기 상품을 직접 판매하는 버전. 입점·판매자센터·정산·상품 승인 제외, 46개 화면. 상품관리는 섹션형 등록·옵션 조합·고시정보·재고·엑셀 일괄등록 포함 |
| `standalone/shop.html` | 독립몰 사용자 | 입점 브랜드·판매자 페이지 제외, 배송비 정책 하나로 계산 |

## 기획서
| 버전 | 관리자 | 사용자 |
|------|--------|--------|
| 입점형 | [관리자 전체 기획서](https://claude.ai/artifact/2t2dGda7gNGyQ1EGmnfum4) | [사용자 전체 기획서](https://claude.ai/artifact/SwDqbwdHwUzdnBPcNVHsfP) |
| 독립몰 | [독립몰 관리자 기획서](https://claude.ai/artifact/SrAkUAmEsGHdKbJP82eBDT) | [독립몰 사용자 기획서](https://claude.ai/artifact/GWeb7PPgjNzVtA4GHQ9hGD) |

## 열기
- 로컬: `index.html` / `shop.html`을 브라우저로 열기
- GitHub Pages(설정 시): `https://nbjiu1011.github.io/tago-shoppingmall-prototype/` (관리자), `.../shop.html` (사용자)

## 특징
- 클릭 인터랙션: 상세·수정·삭제·추가 모달, 장바구니/주문 흐름, 탭·아코디언, 저장 토스트
- 다크/라이트 테마, 모바일 반응형
- 기준 IA: shop1.sinbiweb.net 관리자/스토어프론트 분석

> 데이터는 레이아웃 확인용 샘플이며 실제 DB 연동이 아닌 프로토타입입니다.
