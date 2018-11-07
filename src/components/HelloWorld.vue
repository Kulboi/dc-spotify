<template>
  <main>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-md-2" id="controls">
                    <a href="#" class="mr-4">
                        <i class="fa fa-arrow-left"></i>
                    </a>
                    
                    <a href="#">
                        <i class="fa fa-arrow-right"></i>
                    </a>
                </div>
            
                <div class="col-md-6">
                    <div class="input-group" id="search">
                        <div class="input-group-prepend">
                            <span class="input-group-text" id="inputGroupPrepend2">
                                <i class="fa fa-search"></i>
                            </span>
                        </div>
                        <input type="text" class="form-control" placeholder="Search music...">
                    </div>
                </div>
            
                <div class="col-md-4">
                    <div class="float-right">
                        <div class="avatar avatar-sm">
                            <img src="./../assets/media/profile_img.jpg" alt="..." class="avatar-img rounded-circle">
                        </div>
                        <span class="text-white">John Obi</span>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <section class="artist-hero" style="background: linear-gradient(
      rgba(46, 50, 53, 0.8),
      rgba(46, 50, 53, 0.8)
    ), url('./../assets/media/john_mayer.jpg')">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h1 class="artist-fullname text-white mb-1">
                        <strong>John Mayer</strong>
                    </h1>
                    <h5 class="text-muted">6,184,580 listeners a month</h5>
                </div>

                <div class="col-auto pt-3">
                    <button class="btn">
                        <i class="fa fa-play"></i> Play
                    </button>
                    <button class="btn">Follow</button>
                    <button class="btn">
                        <i class="fa fa-ellipsis-h"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section class="main-content">
        <aside class="menu py-5 pl-4">
            <div class="container">
                <div class="mb-5">
                    <h4 class="text-muted">DISCOVER</h4>
                    <ul class="list-unstyled pl-1">
                        <li class="list-item">
                            <a href="">
                              <i class="fa fa-step-forward"></i>  Start
                            </a>
                        </li>
                        <li class="list-item">
                            <a href="#">
                              <i class="fa fa-headphones mr-2"></i>  Radio
                            </a>
                        </li>
                        <li class="list-item">
                            <a href="#">
                              <i class="fa fa-users"></i>  Activity
                            </a>
                        </li>
                        <li class="list-item">
                            <a href="#">
                              <i class="fa fa-list-alt mr-2"></i>  Library
                            </a>
                        </li>
                        <li class="list-item">
                            <a href="#">
                              <i class="fa fa-heart mr-2"></i>  Weekly Tips
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-muted">PLAYLISTS</h4>
                    <ul class="list-unstyled pl-1">
                        <li class="list-item">
                            <a href="">
                                <i class="fa fa-music mr-2"></i> Vibes
                            </a>
                        </li>
                        <li class="list-item">
                            <a href="#">
                                <i class="fa fa-music mr-2"></i> Friday Tunes
                            </a>
                        </li>
                        <li class="list-item">
                            <a href="#">
                                <i class="fa fa-music mr-2"></i> Office Songs
                            </a>
                        </li>
                        <li class="list-item">
                            <a href="#" class="text-muted">
                                <i class="fa fa-plus"></i> New Playlist
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </aside>

        <div class="songs">
            <div class="container">
                <div class="row">
                    <div class="col-md-6">
                        <h4 class="text-muted mb-4">MOST POPULAR TRACKS</h4>
                        <ul class="list-group">
                            <li class="list-group-item">
                                <div class="row">
                                    <div class="col-1 text-muted">1.</div>
                                    <div class="col-8 text-white">XO</div>
                                    <div class="col-3 text-muted">80,344,300</div>
                                </div>
                            </li>
                            <li class="list-group-item">
                                <div class="row">
                                    <div class="col-1 text-muted">2.</div>
                                    <div class="col-8 text-white">Free fallin'</div>
                                    <div class="col-3 text-muted">51,344,300</div>
                                </div>
                            </li>
                            <li class="list-group-item">
                                <div class="row">
                                    <div class="col-1 text-muted">3.</div>
                                    <div class="col-8 text-white">Mary</div>
                                    <div class="col-3 text-muted">120,344,300</div>
                                </div>
                            </li>
                            <li class="list-group-item">
                                <div class="row">
                                    <div class="col-1 text-muted">4.</div>
                                    <div class="col-8 text-white">Who you love</div>
                                    <div class="col-3 text-muted">41,344,300</div>
                                </div>
                            </li>
                            <li class="list-group-item">
                                <div class="row">
                                    <div class="col-1 text-muted">5.</div>
                                    <div class="col-8 text-white">Who says</div>
                                    <div class="col-3 text-muted">68,344,300</div>
                                </div>
                            </li>
                        </ul>
                    </div>

                    <div class="col-md-2"></div>
                
                    <div class="col-md-4">
                        <h4 class="text-muted mb-4">SIMILAR ARTISTS</h4>

                        <ul class="list-group">
                            <li class="list-group-item">
                                <span class="mr-3 text-muted">1.</span>
                                <span class="text-white">Jason Mraz</span>
                            </li>
                            <li class="list-group-item">
                                <span class="mr-3 text-muted">2.</span>
                                <span class="text-white">Howie Day</span>
                            </li>
                            <li class="list-group-item">
                                <span class="mr-3 text-muted">3.</span>
                                <span class="text-white">Jack Johnson</span>
                            </li>
                            <li class="list-group-item">
                                <span class="mr-3 text-muted">4.</span>
                                <span class="text-white">James Morrison</span>
                            </li>
                            <li class="list-group-item">
                                <span class="mr-3 text-muted">5.</span>
                                <span class="text-white">Matt Nathansson</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
  </main>
</template>

<script>
import axios from 'axios'

export default {
  name: 'HelloWorld',
  data () {
    return {
      api_key: '',
      songs: {},
      artists: {}
    }
  },
  methods: {
    async getRelatedArtists() {
      try {
        let res = await axios.get('https://api.spotify.com/v1/artists', {
          headers: {
            'api_key': ''
          }
        })
        this.artists = res.data.data
      }catch (e) {
        console.log(e)
      }
    },

    async getSimilarSongs() {
      try {
         let res = await axios.get('https://api.spotify.com/v1/search', {
          headers: {
            'api_key': ''
          }
        })
        this.songs = res.data.data
      }catch (e) {
        console.log(e)
      }
    }
  },
  created() {
    this.getRelatedArtists()
  }
}
</script>

<style scoped src="./style.css"></style>
