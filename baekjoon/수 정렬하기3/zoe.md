[문제링크] https://www.acmicpc.net/problem/10989  <br/>
[블로그] https://zoe21.tistory.com/255

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int N = sc.nextInt();
		int numbers[] = new int[N];
		for (int i = 0; i < N; i++) {
			numbers[i] = sc.nextInt();
		}
		Arrays.sort(numbers); 
		System.out.println(Arrays.toString(numbers));

	}
