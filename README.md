# product.product-landing.json
{
  "sections": {
    "main": {
      "type": "main-product",
      "blocks": {
        "price": {
          "type": "price",
          "settings": {}
        },
        "variant_picker": {
          "type": "variant_picker",
          "settings": {
            "variant_labels": true,
            "picker_type": "button",
            "product_dynamic_variants_enable": true,
            "color_swatches": true
          }
        },
        "sales_point": {
          "type": "sales_point",
          "settings": {
            "icon": "globe",
            "text": "Free worldwide shipping"
          }
        },
        "inventory_status": {
          "type": "inventory_status",
          "settings": {
            "inventory_threshold": 10,
            "inventory_transfers_enable": true
          }
        },
        "buy_buttons": {
          "type": "buy_buttons",
          "settings": {
            "show_dynamic_checkout": true,
            "surface_pickup_enable": true
          }
        },
        "description": {
          "type": "description",
          "settings": {
            "is_tab": false
          }
        },
        "tab-1": {
          "type": "tab",
          "settings": {
            "title": "Size chart",
            "content": ""
          }
        },
        "tab": {
          "type": "tab",
          "settings": {
            "title": "Shipping information",
            "content": "<p>Use collapsible tabs for more detailed information that will help customers make a purchasing decision.</p><p>Ex: Shipping and return policies, size guides, and other common questions.</p>"
          }
        },
        "contact": {
          "type": "contact",
          "settings": {
            "title": "Ask a question",
            "phone": false
          }
        },
        "share": {
          "type": "share",
          "settings": {}
        }
      },
      "block_order": [
        "price",
        "variant_picker",
        "sales_point",
        "inventory_status",
        "buy_buttons",
        "description",
        "tab-1",
        "tab",
        "contact",
        "share"
      ],
      "settings": {
        "product_image_size": "large",
        "product_image_type": "slider",
        "thumbnail_height": "flexible",
        "product_zoom_enable": true,
        "enable_video_looping": true,
        "product_video_style": "muted",
        "sku_enable": false
      }
    },
    "countdown": {
      "type": "countdown",
      "blocks": {
        "content": {
          "type": "content",
          "settings": {}
        },
        "timer": {
          "type": "timer",
          "settings": {
            "year": "2023"
          }
        },
        "button": {
          "type": "button",
          "settings": {}
        }
      },
      "block_order": [
        "content",
        "timer",
        "button"
      ],
      "settings": {
        "text_color": "#ffffff",
        "background_color": "#30312c",
        "overlay_color": "#272727",
        "overlay_opacity": 86
      }
    },
    "sub": {
      "type": "product-full-width",
      "settings": {
        "max_width": false
      }
    },
    "text-columns-1": {
      "type": "text-columns",
      "blocks": {
        "text_block-1": {
          "type": "text_block",
          "settings": {
            "image_width": 60,
            "title": "Free shipping",
            "text": "<p>Not sure if this will fit? No problem, send it back for free until you get the right size. Return within 30 days without hassle.</p>"
          }
        },
        "text_block-2": {
          "type": "text_block",
          "settings": {
            "image_width": 70,
            "title": "Direct pricing",
            "text": "<p>We're able to keep quality high and costs low by selling direct to you and avoiding traditional retailing fees.</p>"
          }
        },
        "text_block-3": {
          "type": "text_block",
          "settings": {
            "image_width": 70,
            "title": "Free shipping",
            "text": "<p>Made in Canada using 100% ethically-sourced and sustainable materials. We believe in the long term.</p>"
          }
        }
      },
      "block_order": [
        "text_block-1",
        "text_block-2",
        "text_block-3"
      ],
      "settings": {
        "title": "Why Asana?",
        "alt": false
      }
    },
    "scrolling-text": {
      "type": "scrolling-text",
      "settings": {
        "text_size": 20,
        "color_scheme": "text"
      }
    },
    "hero-video": {
      "type": "hero-video",
      "settings": {
        "title": "Our brand new\nsummer lineup.",
        "title_size": 54,
        "subheading": "",
        "link_text": "Shop leggings",
        "color_accent": "#ffffff"
      }
    },
    "product-recommendations": {
      "type": "product-recommendations",
      "settings": {}
    },
    "collection-return": {
      "type": "collection-return",
      "settings": {}
    },
    "image-compare": {
      "type": "image-compare",
      "blocks": {
        "image-1": {
          "type": "image",
          "settings": {}
        },
        "image-2": {
          "type": "image",
          "settings": {}
        }
      },
      "block_order": [
        "image-1",
        "image-2"
      ],
      "settings": {
        "height": 500,
        "color": "#ffffff"
      }
    },
    "text-columns-2": {
      "type": "text-columns",
      "blocks": {
        "text_block-1": {
          "type": "text_block",
          "settings": {
            "title": ""
          }
        },
        "text_block-2": {
          "type": "text_block",
          "settings": {
            "image_width": 280,
            "title": "Buy a legging  and get the matching bra for 1/2 price!",
            "text": "<p>When you purchase a SET, you can be guaranteed that you're going to be the best-dressed person at the gym, on the track, in the studio, or wherever you're wearing your amazing new gear. Slightly high-waisted means the waist hits just below the belly button.</p>"
          }
        }
      },
      "block_order": [
        "text_block-1",
        "text_block-2"
      ],
      "settings": {
        "title": "",
        "alt": false
      }
    }
  },
  "order": [
    "main",
    "countdown",
    "sub",
    "text-columns-1",
    "scrolling-text",
    "hero-video",
    "product-recommendations",
    "collection-return",
    "image-compare",
    "text-columns-2"
  ]
}
