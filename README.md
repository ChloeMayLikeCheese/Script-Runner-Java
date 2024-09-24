# Script-Runner-Java
A script runner for java

# 

Usage example:

public class Main {
    public static void main(String[] args) {
        // Specify the path to your Bash script
        String scriptPath = "./script.sh";

        // Create an instance of BashScriptRunner and run the script
        BashScriptRunner runner = new BashScriptRunner(scriptPath);
        runner.runScript();
    }
}
