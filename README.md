public class Location {
    
    
    // Name and Type of Locatioon
    private String name;
    private String type;
    
    //constructor
    public Location(String name, String type){
        this.name = name;
        this.type = type;
        
        
    }
    
    public String getName(){
        return name;
    }
    
    public String getType(){
        return type;
    }
    
    public void setTyoe(String type){
        this.type = type;
        
    }
    
    public String toString(){
        return name +  
