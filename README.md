# java-programclass Employee{
    int empid;
    String empname;
    Employee(int eno, String ename ){
        this.empid=eno;
        this.empname=ename;
    }
    void display(){
        System.out.println("employee id:"+this.empid);
        System.out.println("Employee name:"+this.empname);
    }
