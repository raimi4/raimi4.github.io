{
  "settings": {
    "name": "My Site",
    "currentPage": "page1.html",
    "theme": {
      "name": "mobirise4",
      "title": "Mobirise 4",
      "styling": {
        "primaryColor": "#149dcc",
        "secondaryColor": "#ff3366",
        "successColor": "#F7ED4A",
        "infoColor": "#82786E",
        "warningColor": "#879A9F",
        "dangerColor": "#B1A374",
        "mainFont": "Rubik",
        "display1Font": "Rubik",
        "display1Size": 4.25,
        "display2Font": "Rubik",
        "display2Size": 3,
        "display5Font": "Rubik",
        "display5Size": 1.5,
        "display7Font": "Rubik",
        "display7Size": 1,
        "display4Font": "Rubik",
        "display4Size": 1,
        "isRoundedButtons": true,
        "isAnimatedOnScroll": false,
        "isScrollToTopButton": false
      },
      "additionalSetColors": [
        "#ffcc95",
        "#07134c",
        "#ffdeba",
        "#10033b"
      ]
    },
    "path": "@PROJECT_PATH@",
    "siteFonts": [
      {
        "css": "'Rubik', sans-serif",
        "name": "Rubik",
        "url": "https://fonts.googleapis.com/css?family=Rubik:300,400,500,600,700,800,900,300i,400i,500i,600i,700i,800i,900i"
      }
    ],
    "versionFirst": "4.7.6",
    "uniqCompNum": 20,
    "versionPublish": "4.12.0",
    "imageResize": true,
    "screenshot": "screenshot.png",
    "favicon": false,
    "robotsSwitcher": false,
    "sitemapSwitcher": false,
    "sitemapSwitcherAuto": false,
    "siteUrl": false,
    "cookiesAlert": false,
    "gdpr": false
  },
  "pages": {
    "index.html": {
      "settings": {
        "main": true,
        "title": "Home",
        "meta_descr": "",
        "header_custom": "",
        "footer_custom": "",
        "html_before": ""
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"https://mobirise.com\">\n                         <img src=\"@PROJECT_PATH@/assets/images/logo2.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-black\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\"><span class=\"mobi-mbri mobi-mbri-layers mbr-iconfont mbr-iconfont-btn\"></span></a><a class=\"navbar-caption text-black\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\" style=\"background-color: rgb(255, 255, 255); display: inline !important;\"><font face=\"Moririse2\"><span style=\"font-size: 25.6px; font-weight: normal;\"></span></font></a><font face=\"Moririse2\"><a class=\"navbar-caption text-black\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\" style=\"background-color: rgb(255, 255, 255); display: inline !important;\">&nbsp; &nbsp;Interior</a></font></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-black\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Введите Текст\">\n                        <span class=\"mbri-home mbr-iconfont mbr-iconfont-btn\"></span>\n                        Services\n                    </a>\n                </li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-0",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#767676\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL SCREEN INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Click any text to edit or style it. Select text to insert a link. Click blue \"Gear\" icon in the top right corner to hide/show buttons, text, title and change the block background. Click red \"+\" in the bottom right corner to add a new block. Use the top left menu to create new pages, sites and add themes.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\">\n                    <a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n                </div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTkA127IK8",
          "_anchor": "header2-1",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".content": {
              "@media (max-width: 767px)": {
                "text-align": "center",
                "> div:not(:last-child)": {
                  "margin-bottom": "2rem"
                }
              }
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7.5rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#fff",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "flex-wrap": "wrap",
                "justify-content": "flex-end",
                "-webkit-justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#fff"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "justify-content": "center",
                  "-webkit-justify-content": "center"
                }
              }
            }
          },
          "_name": "footer1",
          "_customHTML": "<section group=\"Footers\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline=\"\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline=\"\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked=\"\">\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\">0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\" selected=\"\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax=\"\">\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#2e2e2e\" selected=\"\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked=\"\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#3C3C3C\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n        <input type=\"range\" inline=\"\" title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay &amp;&amp; bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row content text-white\">\n            <div class=\"col-12 col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.com/\">\n                        <img src=\"../_images/logo2.png\" alt=\"Mobirise\">\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Address\n                </h5>\n                <p class=\"mbr-text\">\n                    1234 Street Name\n                    <br>City, AA 99999\n                </p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Contacts\n                </h5>\n                <p class=\"mbr-text\">\n                    Email: support@mobirise.com\n                    <br>Phone: +1 (0) 000 0000 001\n                    <br>Fax: +1 (0) 000 0000 002\n                </p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Links\n                </h5>\n                <p class=\"mbr-text\">\n                    <a class=\"text-primary\" href=\"https://mobirise.com/\">Website builder</a>\n                    <br><a class=\"text-primary\" href=\"https://mobirise.com/mobirise-free-win.zip\">Download for Windows</a>\n                    <br><a class=\"text-primary\" href=\"https://mobirise.com/mobirise-free-mac.zip\">Download for Mac</a>\n                </p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-sm-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-sm-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2017 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-twitter socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>\n",
          "_cid": "qTkAaeaxX5",
          "_anchor": "footer1-2",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page1.html": {
      "settings": {
        "meta_descr": "Site Builder Description",
        "title": "Page 1",
        "order": 1
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\">\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\" checked>\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"https://mobirise.com\">\n                         <img src=\"@PROJECT_PATH@/assets/images/logo2.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-black\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\"><span class=\"mobi-mbri mobi-mbri-layers mbr-iconfont mbr-iconfont-btn\"></span></a><a class=\"navbar-caption text-black\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\" style=\"background-color: rgb(255, 255, 255); display: inline !important;\"><font face=\"Moririse2\"><span style=\"font-size: 25.6px; font-weight: normal;\"></span></font></a><font face=\"Moririse2\"><a class=\"navbar-caption text-black\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\" style=\"background-color: rgb(255, 255, 255); display: inline !important;\">&nbsp; &nbsp;Interior</a></font></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-black\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Введите Текст\">\n                        <span class=\"mbri-home mbr-iconfont mbr-iconfont-btn\"></span>\n                        Services\n                    </a>\n                </li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Введите Текст\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-3",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "H1": {
              "text-align": "right"
            },
            ".mbr-text, .mbr-section-btn": {
              "text-align": "right"
            }
          },
          "_name": "header5",
          "_customHTML": "<section class=\"header5\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Полный экран\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Сверху\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Снизу\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Название\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Текст\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Кнопки\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Стрелка\" name=\"showArrow\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Фоновое изображение\" value=\"@PROJECT_PATH@/assets/images/living-room-2569325-1920-1920x1280.jpg\" parallax selected>\n            <input type=\"color\" title=\"Цвет фона\" value=\"#ffdeba\">\n            <input type=\"video\" title=\"Фоновое видео\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"color\" name=\"color2\" title=\"Цвет 2\" value=\"#10033b\" condition=\"bg.type=='color'\" selected>\n\n        <input type=\"checkbox\" title=\"Наложение\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Цвет наложения\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Прозрачность\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <div class=\"row justify-content-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title align-center pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\">\n                    Дизайн интерьера</h1>\n                <p class=\"mbr-text align-center display-5 pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Это ряд решений, направленных на оформление помещения любого назначения. К ним можно отнести выбор материала для отделки стен, пола, потолка, выбор дверей и окон, проработка вариантов возможного расположения светильников, меблировка и ее планировка. Также тщательно подбираются украшения, аксессуары, различные предметы декора.\n                </p>\n                <div class=\"mbr-section-btn align-center\" mbr-buttons mbr-theme-style=\"display-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Введите Текст\">ПОДРОБНЕЕ</a>\n                        <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Введите Текст\">ДЕМО</a></div>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "sibpOItd3V",
          "_anchor": "header5-5",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Полный экран\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Сверху\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Снизу\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"4\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Название\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Подзаголовок\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Текст\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Кнопки\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Фоновое изображение\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Цвет фона\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Фоновое видео\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Наложение\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Цвет наложения\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Прозрачность\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\">Воплотим вашу идею в жизнь</h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Красивые мобильные сайты\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Мы стараемся и стремимся сделать всё, чтобы вы не отказывались от задуманных планов.&nbsp;Наша цель – это клиенты довольные своим домом.</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-primary-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Введите Текст\">Заказать</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "siomOCZdZL",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header16-i"
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@noSpacing)": {
              ".row": {
                "margin-left": "0",
                "margin-right": "0"
              },
              ".item": {
                "padding-left": "0",
                "padding-right": "0"
              }
            },
            "& when not (@noSpacing)": {
              ".item": {
                "padding-bottom": "2rem"
              }
            },
            "& when (@autoSize)": {
              ".item-wrapper": {
                "height": "100%",
                "img": {
                  "height": "100%",
                  "object-fit": "cover"
                }
              }
            },
            ".carousel-control, .close": {
              "background": "#1b1b1b"
            },
            ".carousel-control-prev": {
              "margin-left": "2.5rem"
            },
            ".carousel-control-next": {
              "margin-right": "2.5rem"
            },
            ".close": {
              "position": "fixed",
              "opacity": ".5",
              "font-size": "35px",
              "font-weight": "300",
              "width": "70px",
              "height": "70px",
              "border-radius": "50%",
              "color": "#fff",
              "top": "2.5rem",
              "right": "2.5rem",
              "line-height": "70px",
              "border": "none",
              "text-align": "center",
              "text-shadow": "none",
              "z-index": "5",
              "-webkit-transition": "opacity .3s ease",
              "-moz-transition": "opacity .3s ease",
              "-o-transition": "opacity .3s ease",
              "transition": "opacity .3s ease",
              "font-family": "'MobiriseIcons'",
              "&::before": {
                "content": "'\\e91a'"
              },
              "&:hover": {
                "opacity": "1",
                "background": "#000",
                "color": "#fff"
              }
            },
            ".carousel-control": {
              "position": "fixed",
              "width": "70px",
              "height": "70px",
              "top": "50%",
              "margin-top": "-35px",
              "line-height": "70px",
              "border-radius": "50%",
              "font-size": "35px",
              "border": "0",
              "opacity": ".5",
              "text-shadow": "none",
              "z-index": "5",
              "color": "#fff",
              "-webkit-transition": "all 0.2s ease-in-out 0s",
              "-o-transition": "all 0.2s ease-in-out 0s",
              "transition": "all 0.2s ease-in-out 0s"
            },
            ".carousel-inner > .active": {
              "display": "block"
            },
            ".carousel-control.left": {
              "left": "0",
              "margin-left": "2.5rem"
            },
            ".carousel-control.right": {
              "right": "0",
              "margin-right": "2.5rem"
            },
            ".carousel-control .icon-next, .carousel-control .icon-prev": {
              "margin-top": "-18px",
              "font-size": "40px",
              "line-height": "27px"
            },
            ".carousel-control:hover": {
              "background": "#1b1b1b",
              "color": "#fff",
              "opacity": "1"
            },
            "@media (max-width: 768px)": {
              ".carousel-control, .carousel-indicators, .modal .close": {
                "position": "fixed"
              }
            },
            "@media (max-width: 767px)": {
              ".mbr-slider .carousel-control": {
                "top": "auto",
                "bottom": "20px"
              },
              ".mbr-slider > .container .carousel-control": {
                "margin-bottom": "0"
              }
            },
            ".carousel-indicators": {
              "bottom": "0",
              "margin-bottom": "3px",
              "@media (max-width: 991px)": {
                "margin-bottom": "3.625rem !important",
                "padding-left": "2.5rem",
                "padding-right": "2.5rem"
              },
              "@media (max-width: 767px)": {
                "display": "none"
              }
            },
            ".carousel-indicators .active, .carousel-indicators li": {
              "width": "7px",
              "height": "7px",
              "margin": "3px",
              "background": "#1b1b1b",
              "opacity": ".5",
              "border": "4px solid #1b1b1b"
            },
            ".carousel-indicators .active": {
              "background": "#fff"
            },
            ".carousel-indicators li": {
              "max-width": "15px",
              "max-height": "15px",
              "border-radius": "50%"
            },
            ".modal": {
              "padding-left": "0 !important",
              "position": "fixed",
              "overflow": "hidden",
              "padding-right": "0 !important"
            },
            ".modal-dialog": {
              "margin": "0 auto",
              "max-width": "100%",
              "padding-left": "1rem",
              "padding-right": "1rem"
            },
            ".modal-content": {
              "border-radius": "0",
              "border": "none",
              "background": "transparent"
            },
            ".modal-body": {
              "padding": "0",
              "display": "flex",
              "align-items": "center",
              "img": {
                "width": "100%",
                "object-fit": "contain",
                "max-height": "calc(100vh - 1.75rem)",
                "height": "fit-content"
              }
            },
            ".carousel": {
              "width": "100%"
            },
            ".modal-backdrop.in": {
              "opacity": ".8"
            },
            ".modal.fade .modal-dialog": {
              "-webkit-transition": "margin-top 0.3s ease-out",
              "-moz-transition": "margin-top 0.3s ease-out",
              "-o-transition": "margin-top 0.3s ease-out",
              "transition": "margin-top 0.3s ease-out"
            },
            ".modal.fade .modal-dialog, .modal.in .modal-dialog": {
              "-webkit-transform": "none",
              "-ms-transform": "none",
              "-o-transform": "none",
              "transform": "none"
            },
            "H4": {
              "color": "#cccccc",
              "text-align": "center"
            }
          },
          "_name": "gallery5",
          "_customHTML": "<section class=\"mbr-gallery gallery5\" group=\"Gallery\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n        <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <header>Size</header>\n        <input type=\"range\" inline title=\"Сверху\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"5\">\n        <input type=\"range\" inline title=\"Снизу\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <header>Show/Hide</header>\n        <input type=\"checkbox\" title=\"Название\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Подзаголовок\" name=\"showSubtitle\" checked>\n        <header>Images</header>\n        <input type=\"checkbox\" title=\"Auto Size\" name=\"autoSize\" checked>\n        <input type=\"checkbox\" title=\"No Spacing\" name=\"noSpacing\">\n        <!-- <input type=\"range\" title=\"Spacing\" name=\"spacing\" min=\"0\" max=\"3\" step=\"0.1\" value=\"1\"> -->\n        <header>Background</header>\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Фоновое изображение\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Цвет фона\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Фоновое видео\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <header condition=\"bg.type!==color\">Наложение</header>\n        <input type=\"checkbox\" title=\"Наложение\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Цвет наложения\" name=\"overlayColor\" value=\"#efefef\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Прозрачность\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.8\" condition=\"overlay && bg.type !== 'color'\">\n        <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <h3 class=\"mbr-section-title align-center mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\">\n            Галерея\n        </h3>\n        <h4 class=\"mbr-section-subtitle align-center pb-4 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">Примеры проектов</h4>\n        <div class=\"row mbr-gallery\" data-toggle=\"modal\" data-target=\"#{{idGallery}}Modal\">\n            <div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/home-1680800-1920-510x339.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"0\" title>\n                </div>\n            </div>\n            <div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/kitchen-1687121-1920-510x264.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"1\" title>\n                </div>\n            </div><div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/kitchen-2174593-1920-510x334.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"2\" title>\n                </div>\n            </div>\n            <div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/apartment-1851201-1920-510x339.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"3\" title>\n                </div>\n            </div>\n            <div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/kitchen-2165756-1920-510x338.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"4\" title>\n                </div>\n            </div><div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/kitchen-2565105-1920-510x340.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"5\" title>\n                </div>\n            </div><div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/chairs-2181968-1920-510x336.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"6\" title>\n                </div>\n            </div><div class=\"col-sm-6 col-md-4 col-lg-3 item gallery-image\">\n                <div class=\"item-wrapper\">\n                    <img class=\"w-100\" src=\"@PROJECT_PATH@/assets/images/dining-room-3108037-1280-510x304.jpg\" alt data-target=\"#lb-{{idGallery}}\" data-slide-to=\"7\" title>\n                </div>\n            </div>\n        </div>\n\n        <div class=\"modal mbr-slider fade\" id=\"{{idGallery}}Modal\" tabindex=\"-1\" role=\"dialog\" aria-hidden=\"true\">\n            <div class=\"modal-dialog\" role=\"document\">\n                <div class=\"modal-content\">\n                    <div class=\"modal-body\">\n                        <div id=\"lb-{{idGallery}}\" class=\"carousel slide\" data-ride=\"carousel\">\n                            <div class=\"carousel-inner\">\n                                <div class=\"carousel-item active\">\n                                    <img class=\"d-block w-100\" src=\"../_images/background1.jpg\" alt>\n                                </div>\n                                <div class=\"carousel-item\">\n                                    <img class=\"d-block w-100\" src=\"../_images/background2.jpg\" alt>\n                                </div><div class=\"carousel-item\">\n                                    <img class=\"d-block w-100\" src=\"@PROJECT_PATH@/assets/images/mbr-1920x1297.jpg\" alt>\n                                </div>\n                                <div class=\"carousel-item\">\n                                    <img class=\"d-block w-100\" src=\"../_images/background3.jpg\" alt>\n                                </div>\n                                <div class=\"carousel-item\">\n                                    <img class=\"d-block w-100\" src=\"../_images/background4.jpg\" alt>\n                                </div><div class=\"carousel-item\">\n                                    <img class=\"d-block w-100\" src=\"@PROJECT_PATH@/assets/images/mbr-1920x1280.jpg\" alt>\n                                </div><div class=\"carousel-item\">\n                                    <img class=\"d-block w-100\" src=\"@PROJECT_PATH@/assets/images/mbr-1-1920x1280.jpg\" alt>\n                                </div><div class=\"carousel-item\">\n                                    <img class=\"d-block w-100\" src=\"@PROJECT_PATH@/assets/images/mbr-2-1920x1280.jpg\" alt>\n                                </div>\n                            </div>\n                            <ol class=\"carousel-indicators\">\n                                <li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"0\" class=\"active\"></li>\n                                <li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"1\"></li><li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"2\"></li>\n                                <li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"3\"></li>\n                                <li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"4\"></li><li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"5\"></li><li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"6\"></li><li data-target=\"#lb-{{idGallery}}\" data-slide-to=\"7\"></li>\n                            </ol>\n                            <a role=\"button\" href class=\"close\" data-dismiss=\"modal\" aria-label=\"Close\">\n                            </a>\n                            <a class=\"carousel-control-prev carousel-control\" href=\"#lb-{{idGallery}}\" role=\"button\" data-slide=\"prev\">\n                                <span class=\"mbri-left mbr-iconfont\" aria-hidden=\"true\"></span>\n                                <span class=\"sr-only\">Назад</span>\n                            </a>\n                            <a class=\"carousel-control-next carousel-control\" href=\"#lb-{{idGallery}}\" role=\"button\" data-slide=\"next\">\n                                <span class=\"mbri-right mbr-iconfont\" aria-hidden=\"true\"></span>\n                                <span class=\"sr-only\">Вперед</span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "sibuTdFs87",
          "_anchor": "gallery5-h",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".title": {
              "margin-bottom": "2rem"
            },
            ".mbr-section-subtitle": {
              "color": "#767676"
            },
            "a:not([href]):not([tabindex])": {
              "color": "#fff",
              "border-radius": "3px"
            },
            "a.btn-white:not([href]):not([tabindex])": {
              "color": "#333"
            },
            "textarea.form-control": {
              "min-height": "188px"
            }
          },
          "_name": "form1",
          "_customHTML": "<section class=\"mbr-section form1\" group=\"Forms\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Сверху\" name=\"paddingTop\" min=\"0\" max=\"8\" value=\"4\">\n        <input type=\"range\" inline title=\"Снизу\" name=\"paddingBottom\" min=\"0\" max=\"8\" value=\"4\">\n\n        <input type=\"checkbox\" title=\"Название\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Подзаголовок\" name=\"showSubtitle\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Фоновое изображение\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Цвет фона\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Фоновое видео\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Наложение\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Цвет наложения\" name=\"overlayColor\" value=\"#c1c1c1\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Прозрачность\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <div class=\"row justify-content-center\">\n            <div class=\"title col-12 col-lg-8\">\n                <h2 mbr-if=\"showTitle\" class=\"mbr-section-title align-center pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\">Контактная форма</h2>\n                <h3 mbr-if=\"showSubtitle\" class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-section-subtitle\"></h3>\n            </div>\n        </div>\n    </div>\n    <div class=\"container\">\n        <div class=\"row justify-content-center\">\n            <div mbr-form class=\"media-container-column col-lg-8\">\n                <!---Formbuilder Form--->\n                <form action name=\"Mobirise Form\" method=\"POST\" class=\"mbr-form form-with-styler\">\n                    <div class=\"row\">\n                        <div hidden=\"hidden\" data-form-alert class=\"alert alert-success col-12\">Спасибо за заполнение анкеты!</div>\n                        <div hidden=\"hidden\" data-form-alert-danger class=\"alert alert-danger col-12\">\n                        </div>\n                    </div>\n                    <div class=\"dragArea row\">\n                        <div class=\"col-md-4  form-group\" data-for=\"name\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"name\" class=\"form-control-label mbr-fonts-style\">Имя</label>\n                            <input type=\"text\" name=\"name\" data-form-field=\"Name\" mbr-theme-style=\"display-7\" required=\"required\" class=\"form-control\">\n                        </div>\n                        <div class=\"col-md-4  form-group\" data-for=\"email\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"email\" class=\"form-control-label mbr-fonts-style\">Email</label>\n                            <input type=\"email\" name=\"email\" data-form-field=\"Email\" mbr-theme-style=\"display-7\" required=\"required\" class=\"form-control\">\n                        </div>\n                        <div data-for=\"phone\" class=\"col-md-4  form-group\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"phone\" class=\"form-control-label mbr-fonts-style\">Телефон</label>\n                            <input type=\"tel\" name=\"phone\" data-form-field=\"Phone\" mbr-theme-style=\"display-7\" class=\"form-control\">\n                        </div>\n                        <div data-for=\"message\" class=\"col-md-12 form-group\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"message\" class=\"form-control-label mbr-fonts-style\">Сообщение</label>\n                            <textarea name=\"message\" data-form-field=\"Message\" mbr-theme-style=\"display-7\" class=\"form-control\"></textarea>\n                        </div>\n                        <div class=\"col-md-12 input-group-btn align-center\" mbr-buttons=\"true\" mbr-theme-style=\"display-4\" data-toolbar=\"-mbrBtnMove,-mbrBtnLink,-mbrBtnAdd\">\n                            <a type=\"submit\" class=\"btn btn-primary btn-form\">ОТПРАВИТЬ</a>\n                        </div>\n                    </div>\n                </form><!---Formbuilder Form--->\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "sibqhUwk9F",
          "_anchor": "form1-6",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(0deg, @color2, @bg-value)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-iconfont-social": {
              "font-size": "32px",
              "color": "@iconsColor"
            },
            ".social-list": {
              "a:focus": {
                "text-decoration": "none"
              }
            }
          },
          "_name": "social-buttons2",
          "_customHTML": "<section group=\"Social\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" plugins=\"SocialLikes\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input inline type=\"range\" title=\"Сверху\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"2\">\n        <input inline type=\"range\" title=\"Снизу\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"2\">\n        <input type=\"checkbox\" title=\"Название\" name=\"showTitle\">\n        \n        <input type=\"color\" title=\"Иконки - Цвет\" name=\"iconsColor\" value=\"#232323\"> \n        <select title=\"Иконки\" name=\"iconsCount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\" selected>4</option>\n            <option value=\"5\">5</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Фоновое изображение\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Цвет фона\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Фоновое видео\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Цвет 2\" name=\"color2\" condition=\"bg.type=='color'\" value=\"#ffffff\">\n        <input type=\"checkbox\" title=\"Наложение\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Цвет наложения\" name=\"overlayColor\" value=\"#efefef\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" title=\"Прозрачность\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-md-8 align-center\">\n                <h2 class=\"pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\">\n                    СЛЕДИТЕ ЗА НАМИ!\n                </h2>\n                <div class=\"social-list pl-0 mb-0\">\n                    <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-twitter socicon mbr-iconfont mbr-iconfont-social\"></span>\n                    </a>\n                    <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-facebook socicon mbr-iconfont mbr-iconfont-social\" mbr-if=\"iconsCount > 1\"></span>\n                    </a>\n                    <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-instagram socicon mbr-iconfont mbr-iconfont-social\" mbr-if=\"iconsCount > 2\"></span>\n                    </a>\n                    <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-youtube socicon mbr-iconfont mbr-iconfont-social\" mbr-if=\"iconsCount > 3\"></span>\n                    </a>\n                    <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                        <span mbr-icon class=\"px-2 socicon-behance socicon mbr-iconfont mbr-iconfont-social\" mbr-if=\"iconsCount > 4\"></span>\n                    </a>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "sibqmVvBNJ",
          "_anchor": "social-buttons2-7",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    }
  }
}
