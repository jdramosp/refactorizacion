package refactorizacion;

class User {

    void setId(String string) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }

    void setName(String julio_Ramos) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }

    void setBirthady(String string) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }
    
}


/----------------------------------------------          ---------------------------------------------------------------------/


package refactorizacion;

import java.util.Date;

public class refactorizacion {
    
        public static void main(String[] args) {
     
        
        User firstUser = new User ();
        Date birthday = new Date(18/11/1993);
        firstUser.setId("001");
        firstUser.setName("Julio Ramos");
        firstUser.setBirthady("18/11/1993");
        System.out.println(firstUser.toString());
        
    }
    
}
