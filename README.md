# this-keyword
 class Some{
	int var;
	public static void main(String[] args) {
		Some ref = new Some();
		ref.func();
		System.out.println(ref.var);
	}


	void func(){
		this.var = 675; this refers too....current execution object
		met(); //this.met();
	}

	void met(){
		System.out.println("Inside met...");
	}
}

