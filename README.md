# ma
WICS HackOverflow 2018


 public class story {
        private String storyContent;
        private String title;
        private ArrayList<String> tags;
        private String date;
        private Integer ID;

        public story(String title){
            addTitle(title);
        }

        public void addTitle(String title ){
            this.title.equals(title );
        }

        public void addStory(String story) {
            this.storyContent.equals(story);
        }

        public void addTag(String tag){
            this.tags.add(tag);
        }

        public void addDate (String month, Integer Day, Integer inputYear){
;            this.date.equals(month + " " + Day + ", " + inputYear);
        }

        public void addID (Integer index){
            this.ID = index;
        }

    }
