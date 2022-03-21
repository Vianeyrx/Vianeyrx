public class LuckyNumberClass {
    
    static String getHash(String theString){
        return theString.hashCode();
    }
    public static void main(String args[]) {
        String companyName = "Google";
        String programName = "SPS";
        currentYear = 2021;
        int companyHash = getHash(companyName);
        int programHash = getHash(programName);
	 int spsLuckyNumber = companyHash + programHash + currentYear;
    }
}
