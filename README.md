public internal class Vincent {

  private List<string> mSkills = new List<string>();
  private string mName;
  private int mAge;


  public string Skills {
    get { return mSkills; }
    set { mSkills = value; }
  }

  public List<string> Name {
    get { return mName; }
    set { mName = value; }
  }

  public int Age {
    get { return mAge; }
    set { mAge = value; }
  }

  public Vincent() {
    Skills = string["Python", "C#", ".Net", "Move"];
    Name = "Vincent Gagnon";
    Age = 18;
  }
}
