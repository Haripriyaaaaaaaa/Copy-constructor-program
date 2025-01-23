# Copy-constructor-programStudent6(int i,String n){

id = i;

name = n;

}

Student6(Student6 s){

id = s.id;

name =s.name;

}

void display(){System.out.println(id+" "+name);}

public static void main(String args[]){

Student6 s1 = new Student6(20,"haripriya");

Student6 s2 = new Student6(s1);

s1.display();

s2.display();

}

}

OUTPUT

20 haripriya

20 haripriya

BUILD SUCCESSFUL (total time: 0 seconds)
