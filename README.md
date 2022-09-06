# SourceCode<br>

## 유니티에 사용되는 소스코드

---

#Dotween Ease Graph

> How To Use Dotween & Dotween Ease Graph

## How To Use ( 사용법 )

먼저 닷트윈을 사용하는 방법에 대해 알아봅시다.

```cs
using DG.Tweening; //닷트윈 using으로 참조

object.transform.DoMove(new Vecter3(1,1,1), 0.5f).SetEase(Ease.사용할이지이름);
```

아래는 닷트윈의 Ease를 나타낸 그래프 입니다.<br>

<center>
<img src="https://user-images.githubusercontent.com/74443267/147257964-6962c630-0377-4ae4-97c4-ba4c28688d44.gif" width="500" height="550">
</center>
닷트윈 그래프 적용법을 살펴보았습니다.

---

#퍼센트 계산 유틸

> Percent Util Class

<details>
<summary>파일 이름</summary>

- PerUtil.cs
</details>

## #How To Use ( 사용법 )

```cs
//30%의 확률 이벤트
bool doubleAtk = PerUtils.ReturnPercent(30);
if(doubleAtk)
{
  Debug.Log("더블 어택!");
}
```

---

#하이라키 구분 에디터

> Hierarchy Color Divider

<details>
<summary>파일 이름</summary>

- ColorINHierarchy.cs
</details>

## How To Use ( 사용법 )

<center>
1. ColorInHierarchy를 드래그 앤 드롭 or Add Component로 추가한다.<br>
  <br>
   <img src="https://user-images.githubusercontent.com/74443267/177757204-218faae6-eb54-4d6d-b5f2-ec0683616d4c.png" width="400px">
  <br>
  <br>
   2. 오브젝트에 추가 된 모습<br>
   <br>
   <img src="https://user-images.githubusercontent.com/74443267/177757162-b2e65bd7-c038-401d-b328-c2b69d457468.png" width="300">
   <br>
   <br>
   3. 색상 파레트를 열어서 원하는 색상으로 지정

**_<U>주의: 너무 어두운색과 밝은색은 안보일수 있음_**

  <br>
  <img src="https://user-images.githubusercontent.com/74443267/177757362-dad3141c-977e-4999-be1d-ad26e465ba06.png" width="300">
   <br>
   <br>
4. 변경 완료 된 모습<br>
<br>
<img src="https://user-images.githubusercontent.com/74443267/177757376-838ef07d-2b5e-4ef6-ba8f-e6b390c98982.png" width="300">
</center>

---
