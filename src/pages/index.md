---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: section_1
    background_image: images/bee_background_image.jpg
    background_image_opacity: 75
    content: '## **Chào Mừng Bạn Đến Với CTY TNHH Hoa Yêu Thương**'
    actions:
      - title: Xem Sản Phẩm
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: San Pham Chinh
    icon: true
    light_title: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/bigplants.md
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    testimonials:
      - author:
          name: Le Nguyen Yen Nhi
          location: ' TP.HCM'
        text: Mat Ong Ngon Nhat TPHCM!!!!
      - author:
          name: Nguyen Hoang Thien Nhan
          location: ' Edmonton'
        text: 'Nhan vien tan tinh, chu dao. San pham chat luong cao '
  - type: promotion_section
    section_id: promotion_section
    title: Giao Hang Den Tan Nha
    subtitle: Mien Phi
    image: images/pollinating-bee-.jpg
    cta:
      title: Xem Thêm
      url: /store
      style: secondary
template: home
---
