# CopyDirectories-Java
Class for copy directories and his content using Java.

Examples of usage:


public class MainClass {

    public static void main(String[] args) {
        try {            
            String pathSource = "C:\\Data\\books\\"; 
            String pathTarget = "C:\\Data\\backups\\books\\";
            
            CopyDirectories.copy(pathSource, pathTarget);
            
        } catch (IOException ex) {
            Logger.getLogger(CopyDirectories.class.getName()).log(Level.SEVERE, null, ex);
        }

    }
}


Example:

public class MainClass {

    public static void main(String[] args) {
        try {            
            File fSource = new File("C:\\Data\\books\\"); 
            File fTarget = new File("C:\\Data\\backups\\books\\");
            
            CopyDirectories.copy(pathSource, pathTarget);
            
        } catch (IOException ex) {
            Logger.getLogger(CopyDirectories.class.getName()).log(Level.SEVERE, null, ex);
        }

    }
}



