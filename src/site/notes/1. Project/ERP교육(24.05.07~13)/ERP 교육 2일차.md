---
{"dg-publish":true,"permalink":"/1-project/erp-24-05-07-13/erp-2/","tags":["gardenEntry"]}
---

# 오전

## Stock requirement list

1. Transaciton : **md04**
	현재 재고를 차감하면서 앞으로의 계획이 어떻게 흘러가는지 알 수 있음.

2. [[1. Project/ERP교육(24.05.07~13)/재고조회실습\|재고조회실습]]
3. MRP 설명

	![IMG_3141.jpeg](/img/user/IMG_3141.jpeg)


4. [[Excalidraw/Drawing 2024-05-08 09.42.15.excalidraw#^Ums9FB-aDBrbNbmYdrExx\|MRP 흐름예시]]
5. Planning 실습
	T-code : MF50
	![Pasted image 20240508101311.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508101311.png)
	- 조회 후 화면
	![Pasted image 20240508102843.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508102843.png)
	- 계획량 입력하고  계획 fix 시키면, md04에서도 조회 됨.
	- Pldord 더블클릭하면 상세 이력 확인 가능.(Planned order 상세)
		![Pasted image 20240508102649.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508102649.png)
		Exception message 중 위 3개 볼 필요 있음
		- 10 Reschedule in을 특히 주의깊게 봐야 함.
		- 결품되지 않도록 봐야 함. 일정 변경해서 들어와야 한다는 뜻.

6. mrp 실행 실습
		T-code : MD04에서 
		![Pasted image 20240508103321.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508103321.png)
		MD04에서 MRP element 더블클릭해서
		PR생성하거나, PO로 전환하거나 할 수 있음.
		![Pasted image 20240508124154.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508124154.png)
		
7. Salse Order 관련 실습
	VA03에서 Sales order 생성
		![Pasted image 20240508111638.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508111638.png)
	![Pasted image 20240508124035.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508124035.png)

8. Make to order production
![IMG_3145.jpeg](/img/user/IMG_3145.jpeg)



9. 시나리오 실습
	- MRP master setting 화면, 
	![Pasted image 20240508130112.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508130112.png)
		- material master mrp3 view
		  Consuption Mode에서 Foward, backward consumption 설정가능.
		- 나중에 다시 찾아봐야 할 듯
	- Sales order 생성
			![Pasted image 20240508130613.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508130613.png)
		Sales order num. : 376
		![Pasted image 20240508130834.png](/img/user/1.%20Project/ERP%EA%B5%90%EC%9C%A1(24.05.07~13)/Pasted%20image%2020240508130834.png)
		중간에 오더가 추가로 들어오니 리스케줄 제안 들어옴.
		
		  
