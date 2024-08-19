title:: Theme test
description:: page to test appearance
tags:: ⌘/skip-tasks,

- Examples of *page* **properties** `above` ==and *some* **formatted** ***text*** __*with*__ `highlight`==
  id:: 63b8e38c-a943-4ba0-b8d7-ad704453e29e
- Links: [[Theme test]] #tags, [external](http://google.com), ![booklet.pdf](../assets/nvc-booklet_1668037509996_0.pdf)
  id:: 6423a937-76b6-4234-a772-9c42b88cacca
- # Header
  id:: 6423a937-e0c1-47b0-8ebb-e130f9b3a67a
  - NOW [#A] task now
    id:: 634d5d93-5e38-4ca0-9c7a-f42c8378158b
  - WAIT [#B] task wait
    id:: 634dec63-f521-48b6-8b1a-2c1a318a0e28
  - DONE [#C] task done
    id:: 644251cc-34dc-49a2-85cb-85c5c90074de
    SCHEDULED: <2022-10-01 Sat>
  - Reference: ((6423a937-76b6-4234-a772-9c42b88cacca))
    id:: 651efbd5-1a76-44dc-a366-f2915615b7f4
  - Double ((651efbd5-1a76-44dc-a366-f2915615b7f4))
    id:: 634d5efa-2b06-402b-ad48-1de87fb2d770
    - id:: 6423a937-8754-4730-85af-2cf69558ab8c
      > Quote with indent
  - ## Selected Block
    - Sidebar demo
      heading:: true
      - id:: 6369c344-1948-4821-bbec-5c747cbb83b0
        ```python
        version = 3.9
        print(f'Python v{version} code block')

        @decorator
        def f(a, b=True):
          # docstring
          return self.name or None
        ```
      - # Header 1
        background-color:: gray
        id:: 644251cc-16ab-463e-986d-c46331b28ed3
      - ## Header 2
        background-color:: red
      - ### Header 3
        background-color:: yellow
      - #### Header 4
        background-color:: green
      - ##### Header 5
        background-color:: blue
      - ###### Header 6
        background-color:: purple
      - ###### Header 6
        background-color:: pink
        id:: 644251cc-066c-4544-a01a-80b09d5c0b99
      - ### References #.columns
        -
          - 1 [**ref**](((644251cc-16ab-463e-986d-c46331b28ed3)))
            id:: 64424b33-db00-4545-8676-896bebb9a5e9
          - 2 ((64424b33-db00-4545-8676-896bebb9a5e9))
            id:: 64424b44-772f-4b60-abfb-b0e1232b9c60
          - 3 ((64424b44-772f-4b60-abfb-b0e1232b9c60))
            id:: 64424b4c-eb2d-4520-8193-dcddb01b8415
          - 4 ((64424b4c-eb2d-4520-8193-dcddb01b8415))
            id:: 64424b4e-b6b0-4ceb-9994-bd512f3d4579
          - 5 ((64424b4e-b6b0-4ceb-9994-bd512f3d4579))
            id:: 64424b4f-c13a-46f1-927f-90294d80c735
          - 6 ((64424b4f-c13a-46f1-927f-90294d80c735))
            id:: 64424b51-cb52-4487-9f03-4b04b0620f08
        -
          - ((644251cc-34dc-49a2-85cb-85c5c90074de))
            id:: 66894875-8f9b-4681-b6d5-6fedc320bf05
          - ((6423a937-8754-4730-85af-2cf69558ab8c))
    - #.columns
      - Border for parent #.border
        id:: 6423a937-6a72-4d42-9b4e-74de1cbea7c5
        - item 1
        - item 2
      - Border for children #.border-child
        id:: 6423a937-5e26-4091-bdd1-7454557dfbf3
        - item 1
          - sub
        - item 2
    - id:: 64425540-9dff-4303-9819-bba03733dae0
      |Table|header|
      |first|row (odd)|
      |second|row (even)|
      |third|row (odd)|
    - {{query (namespace [[logseq/themes]])}}
      id:: 644251d6-9766-4d20-8c92-eacf6b84bbe1
      query-properties:: [:icon :page :test]
    - highlighted ==page ref [[Theme test]], [link](http://google.com)==
      id:: 6423a937-f1fe-4bfa-bf28-f7f19b54f893
    - Check /date picker and {{cloze cloze}}
      id:: 6423a937-ad97-49e0-a8ed-34099b240a65
    - Check presentation
    -
    - text **header**
      prop:: 123
      id:: 644256fa-887f-44a3-aa36-aca8ce520de0
    - prop:: 456
      id:: 9c8f2daa-09e8-40fd-b306-4a7f422a399c
    -
    - Background grey color with ==highlight==, [link](http://google.com), [[Theme test]]
      background-color:: gray
      id:: 644256ae-be81-4b91-9b3a-686e58c0c06f
    - Background red color with ==highlight==, [link](http://google.com), [[Theme test]]
      background-color:: red
    - Background yellow color with ==highlight==, [link](http://google.com), [[Theme test]]
      background-color:: yellow
    - Background green color with ==highlight==, [link](http://google.com), [[Theme test]]
      background-color:: green
    - Background blue color with ==highlight==, [link](http://google.com), [[Theme test]]
      background-color:: blue
    - Background purple color with ==highlight==, [link](http://google.com), [[Theme test]]
      background-color:: purple
    - Background pink color with ==highlight==, [link](http://google.com), [[Theme test]]
      background-color:: pink
    - ---
    - Flashcard #card
      id:: 66c3280f-92e1-41f9-bc71-64e64c8fd7ff
      - text
    - Flash cards collapsed #card
      collapsed:: true
      - text
    - ---
    - NOW task now
      id:: 6372cb45-3390-4b48-a16f-7204ee7b0698
    - LATER task later
      id:: 6372cb5e-3fd0-4fd8-bfbf-c7aad7f4398e
    - DONE task done
      id:: 6372cb6f-a10a-49f2-9f84-2377f9821283
    - WAIT task wait
      id:: 6372cb66-4298-4e05-b7f6-7642e654a8c4
    - CANCELLED task cancel
      id:: 6372cb7c-97fb-4f0e-95cb-9c706fc0afe8
    - ---
    - LATER task deadline
      id:: 64424ebe-68e4-4a9d-9e24-093c326da3dd
      DEADLINE: <2022-04-22 Sat>
    - LATER task scheduled
      id:: 6423a937-279b-4d90-94c7-e9acfc9baa17
      SCHEDULED: <2022-04-22 Sat 11:53>
    - LATER task mixed
      id:: 64424f18-ca60-48fc-9b77-25f409d9a405
      DEADLINE: <2022-04-22 Fri>
      SCHEDULED: <2022-04-22 Sat 11:53>
    - ---
    - block deadline
      id:: 644258c8-1788-4d9b-ac65-be74d4ecf8dc
      DEADLINE: <2022-04-21 Fri>
    - block scheduled
      id:: 644258ce-f6ae-4996-83b7-5f09524610a3
      SCHEDULED: <2022-04-21 Fri 12:35>
    - block mixed
      id:: 644258e7-3696-4d66-8591-eb7359c262d3
      DEADLINE: <2022-04-21 Thu>
      SCHEDULED: <2022-04-21 Fri 12:35>
    -
    - ![image.png](../assets/image_1687098889273_0.png){:height 200, :width 318}
      id:: 648f1eef-f645-4387-a9fe-eae6bd4ddb4d
    -
    - Admonitions
      id:: 644256ae-3c2c-4d15-9600-ffd55a766600
      heading:: true
      - id:: 63b8e38c-738e-4056-a742-79e47d9b9051
        #+BEGIN_NOTE
        Note
        #+END_NOTE
      - #+BEGIN_PINNED
        Pinned
        #+END_PINNED
      - #+BEGIN_TIP
        Tip
        #+END_TIP
      - #+BEGIN_IMPORTANT
        Important
        #+END_IMPORTANT
      - #+BEGIN_CAUTION
        Caution
        #+END_CAUTION
      - #+BEGIN_WARNING
        Warning
        #+END_WARNING
    -
    - Macros
      heading:: true
      - before {{wrong macro}} after
      - before {{{wrong macro}}} after
      - before {{i f25f}} after
    -
    - Embedding
      heading:: true
      - Page:
        - {{embed [[Theme test]]}}
          id:: 644256ae-44c9-46d1-8222-ade14e052a5d
        - ((644256ae-44c9-46d1-8222-ade14e052a5d))
      - Block:
        id:: 635e191b-7e56-4997-b3ac-79eba758bd8d
        - {{embed ((634d5efa-2b06-402b-ad48-1de87fb2d770))}}
          id:: 644256ae-0ce5-4aa4-a29c-b31a35911143
        - ((644256ae-0ce5-4aa4-a29c-b31a35911143))
      -
      - Props:
        - block props: ((644256fa-887f-44a3-aa36-aca8ce520de0))
        - block props: ((9c8f2daa-09e8-40fd-b306-4a7f422a399c))
        - ((9c8f2daa-09e8-40fd-b306-4a7f422a399c))
      -
      - ((63b8e38c-a943-4ba0-b8d7-ad704453e29e))
      - ((6423a937-76b6-4234-a772-9c42b88cacca))
        - before ((636c6d43-b06f-4726-a2b8-8aa3681e4728)) after
          id:: 66894875-32d7-4237-ba3a-6ce5f661798c
        - ((65146483-1f05-4e6b-b672-a4feb7c0dba9))
        - before ((65146483-1f05-4e6b-b672-a4feb7c0dba9)) after
      - ((6423a937-e0c1-47b0-8ebb-e130f9b3a67a))
      - ((644251cc-16ab-463e-986d-c46331b28ed3))
      - ((644251cc-066c-4544-a01a-80b09d5c0b99))
      - ((644256ae-be81-4b91-9b3a-686e58c0c06f))
      - ((6423a937-f1fe-4bfa-bf28-f7f19b54f893))
      -
      - ((6423a937-6a72-4d42-9b4e-74de1cbea7c5))
      - ((6423a937-5e26-4091-bdd1-7454557dfbf3))
      -
      - Reference with label:
        - [LABEL →](((63b8e38c-a943-4ba0-b8d7-ad704453e29e)))
          id:: 66894875-f8b5-4bed-a17a-89c65b291f58
        - **[LABEL →](((63b8e38c-a943-4ba0-b8d7-ad704453e29e)))**
          id:: 66894875-6d77-49a6-84e7-fbfcdebc1259
        - [**LABEL →**](((63b8e38c-a943-4ba0-b8d7-ad704453e29e)))
          id:: 66894875-c178-4f24-9a92-0971aa4d5acd
      -
      - ((6423a937-8754-4730-85af-2cf69558ab8c))
      -
      - ((6369c344-1948-4821-bbec-5c747cbb83b0))
      -
      - ((644251d6-9766-4d20-8c92-eacf6b84bbe1))
      -
      - ((64425540-9dff-4303-9819-bba03733dae0))
      -
      - ((63b8e38c-738e-4056-a742-79e47d9b9051))
      - ((648f1eef-f645-4387-a9fe-eae6bd4ddb4d))
      -
      - ((66c3280f-92e1-41f9-bc71-64e64c8fd7ff))
      -
      - ((634d5d93-5e38-4ca0-9c7a-f42c8378158b))
      -
      - ((6372cb45-3390-4b48-a16f-7204ee7b0698))
      - ((6372cb5e-3fd0-4fd8-bfbf-c7aad7f4398e))
      - ((6372cb6f-a10a-49f2-9f84-2377f9821283))
      - ((6372cb66-4298-4e05-b7f6-7642e654a8c4))
      - ((6372cb7c-97fb-4f0e-95cb-9c706fc0afe8))
      -
      - ((64424ebe-68e4-4a9d-9e24-093c326da3dd))
      - ((6423a937-279b-4d90-94c7-e9acfc9baa17))
      - ((64424f18-ca60-48fc-9b77-25f409d9a405))
      -
      - ((644258c8-1788-4d9b-ac65-be74d4ecf8dc))
      - ((644258ce-f6ae-4996-83b7-5f09524610a3))
      - ((644258e7-3696-4d66-8591-eb7359c262d3))
      -
      - r1 ((64424ba8-f435-47fa-b7eb-b911c3a5a3e4))
        id:: 64424b83-d11e-491f-b2d2-0536763bd8ad
      - r2 ((64424b83-d11e-491f-b2d2-0536763bd8ad))
        id:: 64424ba8-f435-47fa-b7eb-b911c3a5a3e4
    - ### Icons for properties
      - Logseq
        tags::
        alias::
        file::
        file-path::
        template:: .
        template-including-parent::
      - Other #.columns
        - ```
          unknown::
          tag::
          label::
          ref::
          reference::
          source::
          author::
          creator::
          leading::
          owner::
          assignee::
          who::
          date::
          start::
          end::
          day::
          week::
          month::
          year::
          when::
          duration::
          time::
          location::
          place::
          where::
          related::
          url::
          link::
          text::
          summary::
          description::
          comment::
          note::
          ```
        - ```
          category::
          topic::
          area::
          format::
          set::
          type::
          size::
          level::
          quantity::
          count::
          width::
          height::
          steps::
          version::
          isbn::
          number::
          page::
          task::
          issue::
          project::
          state::
          status::
          formula::
          function::
          percent::
          percentage::
          total::
          sum::
          amount::
          timeline::
          chart::
          progress::
          metric::
          criteria::
          ```
        - ```
          health::
          cardio::
          activity::
          fitness::
          workout::
          exercise::
          stretching::
          yoga::
          walk::
          run::
          rest::
          sleep::
          equipment::
          reps::
          repeat::
          repetitions::
          measure::
          measurement::
          scale::
          weight::
          recipe::
          eat::
          food::
          nutrition::
          calories::
          water::
          coffee::
          alcohol::
          cigarette::
          ```
        - ```
          asc::
          ascending::
          desc::
          descending::
          fingerprint::
          footprint::
          block::
          qr::
          qr-code::
          qrcode::
          code::
          script::
          paragraph::
          section::
          chapter::
          arg::
          param::
          plugin::
          color::
          price::
          rating::
          keyword::
          keywords::
          mode::
          
          creators::
          cast::
          score::
          keyword::
          keywords::
          context::
          ```
    - ### Other
      - {{video https://www.youtube.com/watch?v=kJDxdpy4E1E}}
        - {{youtube-timestamp 100}} go 1
        - {{youtube-timestamp 00:01:45}} go 2
      -
      - ```calc
        2+5
        360/7
        ```
      -
      - #.columns
        - {{renderer block-calendar}}
        - {{renderer :days, @}}
          - ```clojure
            [
              :find (pull ?p [*])
              :where
                [?b :block/refs ?r]
                [?b :block/page ?p]
                [?r :block/name "theme test"]
                [?p :block/journal? true]
            ]
            ```
      - {{renderer :smartblock, Reading Log → New record, Button, false}}
      - Number list
        - item
          logseq.order-list-type:: number
        - item
          logseq.order-list-type:: number
          - sub-item
            logseq.order-list-type:: number
        - item
          logseq.order-list-type:: number
    - ### Levels
      id:: 636ecf85-8100-4373-80d8-cbe9fa8aefb9
      - embed
        id:: 636ecfd7-75b2-4a9e-80bd-11b29bd510c9
      - {{embed ((636ecfd7-75b2-4a9e-80bd-11b29bd510c9))}}
        id:: 636ecf8d-812e-4c37-8f58-feb6d01fbe8f
      - {{embed ((636ecf8d-812e-4c37-8f58-feb6d01fbe8f))}}
        id:: 636ecfa0-c219-440d-ba76-1004f7d3fd3c
      - {{embed ((636ecfa0-c219-440d-ba76-1004f7d3fd3c))}}
        id:: 636ecfab-56f9-4a3b-9c7d-e2afdcce6824
      - {{embed ((636ecfab-56f9-4a3b-9c7d-e2afdcce6824))}}
        id:: 636ecfce-536d-485b-a755-b1bf8f68d0df
      - {{embed ((636ecfce-536d-485b-a755-b1bf8f68d0df))}}
        id:: 636ed003-2286-4a0d-a2c8-624ca79f192c
      - {{embed ((636ed003-2286-4a0d-a2c8-624ca79f192c))}}
        id:: 636f035a-f514-41c1-896a-2a8364f7547d
