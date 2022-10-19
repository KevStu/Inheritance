package DemoInherit;

public class Teacher extends Subject {
    //fields of parent class
    private String designation;
    String collegeName;
    String subjectName;
    String College;
    String strAction;
    Subject subObj = new Subject();

    public Teacher(String designation, String collegeName, String subjectName, String College) {
        super();

        this.designation = designation;
        this.collegeName = collegeName;
        subObj.setSubject(subjectName);
        this.College = College;
    }

    public void setDesignation(String designation) {
        this.designation = designation;
    }

    public String getDesignation() {
        return designation;
    }
    public String getSubjectName() {
        return subObj.subject;
    }

    //method of parent class
    void does(){
        System.out.println("Teaching");
    }
    //overloading
    private void does(String strAction){
        this.strAction = strAction;
        System.out.println("Teaching - " + strAction);
    }

    protected Object College() {
        return  College;
    }
}
