# loading-screen
load screen component or wait for java se

Use this component to create a wait screen in your java applications


Example:

//Any method where its use is required
    public void loginIntervencion(String user, String pass) {

        //An instance of the wait class is implemented and the process to be run is placed inside.
        LoadingScreen result = new LoadingScreen() {
            @Override
            public boolean doSomeThing() {
            
            ......your code that returns true or false....
            
            }
        };

        //The result of the method is obtained if it ran exactly
        if (result.getResult()) {

            
            
           
        //Otherwise a message is displayed
        } else {
    
    
        }

    }
    
    ![image](https://user-images.githubusercontent.com/40126161/192845460-637b0518-60f0-4927-80d3-12a1ded22cc9.png)

    
    
    
    
