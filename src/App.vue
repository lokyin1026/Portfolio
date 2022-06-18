<template>
  <div>
    <my-info/>
    <Particles
        id="tsparticles"
        ref="tsparticles"
        :options='{
  background: {
    color: {
      value: "#FFFFFF"
    },
    position: "50% 50%",
    repeat: "no-repeat",
    size: "cover"
  },
  fullScreen: {
    zIndex: -1
  },
  interactivity: {
    events: {
      onClick: {
        mode: "push"
      },
      onHover: {
        mode: "bubble"
      }
    },
    modes: {
      bubble: {
        distance: 400,
        duration: 2,
        opacity: 0.8,
        color: {
          value: "#ff0000"
        },
        size: 40,
        divs: {
          distance: 200,
          duration: 0.4,
          mix: false,
          selectors: []
        }
      },
      grab: {
        distance: 100
      },
      repulse: {
        divs: {
          distance: 200,
          duration: 0.4,
          factor: 100,
          speed: 1,
          maxSpeed: 20,
          easing: "ease-out-quad",
          selectors: []
        }
      }
    }
  },
  particles: {
    color: {
      value: "#161a37"
    },
    links: {
      color: {
        value: "#ffffff"
      },
      distance: 200,
      width: 2
    },
    move: {
      attract: {
        rotate: {
          x: 600,
          y: 1200
        }
      },
      enable: true,
      path: {},
      outModes: {
        bottom: "out",
        left: "out",
        right: "out",
        top: "out"
      },
      speed: 3,
      spin: {}
    },
    number: {
      density: {
        enable: true
      },
      value: 8
    },
    opacity: {
      random: {
        enable: true,
        minimumValue: 0.3
      },
      value: {
        min: 0.3,
        max: 0.5
      },
      animation: {
        speed: 2,
        minimumValue: 0.1
      }
    },
    rotate: {
      random: {
        enable: true
      }
    },
    shape: {
      options: {
        polygon: {
          sides: 6
        },
        star: {
          sides: 6
        }
      },
      type: "polygon"
    },
    size: {
      random: {
        enable: true,
        minimumValue: 100
      },
      value: {
        min: 30,
        max: 30
      },
      animation: {
        minimumValue: 40
      }
    },
    stroke: {
      width: 4
    }
  }
}'

    />
  </div>


</template>

<script>
import myInfo from './components/Profolio.vue'

export default {
  name: 'App',
  components: {
    myInfo,
  }
}
</script>

<style>


</style>
