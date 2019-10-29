class Song 
  
  attr_accessor :name, :artist, :genre
  
  @@all = []

  def initailize(name,artist,genre)
   @name = name
   @artist = artist
   @genre = genre
   @@all << self
  end 
  
  def self.all
  @@all
  end
  

end

class MusicLibraryController
  
  def list_songs()
   
   @all_songs = song.all
   songs_sorted_by_name = @all_songs.sort_by do |song|
   song.name
  end 

   song_sorted_by_name.each.with_index(1) do |song,index|
   puts "#{index}. #{song.artist} - #{song.name} - #{song.genre}"
   end 
  end 
end 



one_minute.Song.new("One Minute", "The Album Leaf", "Ambient")
Shomolele.Song.new("Shomolele", "Praiz feat Dalo", "Afro Beat")
rain_outside_my_window.Song.new("Rain Outside My Window", "Brillion", "Chill Hop")
try_to_taste.Song.new("Try To Taste", "Eugenio Izzi", "Chill Hop")
quiet.song.new("Quiet", "This Will Destrory You", "Alternative")
over_atlantic_city.Song.new("Over Atlantic City", "Port Blue", "Easy Listening")

def play_song
  list_of_songs = song.all.sort { |a, b| a.name <=> b.name}

  music_controller = music_library_controller.new 
  music_controller.list_songs
  puts "Choose your song."
  input = get.strip.to_i
  
  if(1..song.all.length).include?(input)
  song = list_of_songs [input-1]
  puts "playing #{song.name} by #{song.artist}"
  end 

end 