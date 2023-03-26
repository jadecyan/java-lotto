# 로또게임
## 기능구현
[x]사용자는 구입금액을 입력할 수 있다
[x]사용자는 수동으로 구매할 로또수를 입력할 수 있다.
[x]수동 구매수는 전체 로또수를 넘어갈 수 없다.
[x]1~45까지의 숫자 중에서 랜덤으로 6개를 뽑아서 중복없는 로또번호를 만든다.(수동, 자동 공통)
[x]로또 생성 시 수동, 자동 내역을 출력해서 보여준다.
[x]사용자는 당첨번호, 보너스번호를 입력할 수 있다.
[x]게임횟수를 입력받아서 그만큼 로또번호를 생성한다.
[x]당첨번호 수와 보너스볼 일치여부를 따라서 랭킹을 반환한다.
[x]당첨번호가 1~45중의 숫자가 아니거나 중복되는 번호(보너스번호 포함), 6자리가 아닐 경우 예외처리한다.
[x]랭킹은 LottoRank enum으로 정의한다.
[x]당첨번호 클래스와 구입한 로또를 입력값으로 받아서 결과를 반환한다.
[x]결과값과 실제 구입금액을 비교해서 수익률을 구한다.
[x]결과와 수익률을 출력한다.
[x]수익률이 1보다 작을경우 손해라고 표시한다.

## 기능테스트 목록
[x]구입금액이 제대로 입력되는지 테스트한다.
[x]수동입력에 따라 수동회차, 자동회차가 맞게 세팅되는지 확인한다.
[x]수동번호 입력 규칙에 맞는지 확인한다.
[x]LottoTicket에서 사용되는 로또 정합성 규칙을 확인한다.
[x]입력번호와 보너스 번호가 제대로 입력이 되는지 확인한다.
[x]랭킹을 제대로 찾는지 확인한다.
[x]제대로 된 결과값이 나오는지 테스트한다.
[x]출력값이 예상값과 맞게 나오는지 테스트한다.
