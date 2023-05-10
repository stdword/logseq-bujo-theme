title:: Theme test
description:: page to test appearance
link:: [[Theme test]], [Google](http://google.com)

- Examples of *page* **properties** `above` ==and *some* **formatted** ***text*** __*with*__ `highlight`==
  id:: 63b8e38c-a943-4ba0-b8d7-ad704453e29e
- ![booklet.pdf](../assets/nvc-booklet_1668037509996_0.pdf)
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
    - Wait task reference: ((634dec63-f521-48b6-8b1a-2c1a318a0e28))
    - [[2022-10-17 Mon]] #[[Theme test]] [external link](http://google.com) ((634d5d93-5e38-4ca0-9c7a-f42c8378158b))
      id:: 634dcf1c-3513-4aac-8a23-39279ee4e520
    - Inside block reference
      id:: 634d5efa-2b06-402b-ad48-1de87fb2d770
      ((634dcf1c-3513-4aac-8a23-39279ee4e520))
        - id:: 6423a937-8754-4730-85af-2cf69558ab8c
          > Quote with indent
    - ## Sub header
        - id:: 6369c344-1948-4821-bbec-5c747cbb83b0
          ```python
          version = 3.9
          print(f'Python v{version} code block')
          
          @decorator
          def f(a, b=True):
            # docstring
            return self.name or None
          ```
        - {{query (namespace [[logseq/themes]])}}
          id:: 644251d6-9766-4d20-8c92-eacf6b84bbe1
          query-properties:: [:icon :page :test]
        - # Header 1
          background-color:: gray
          id:: 644251cc-16ab-463e-986d-c46331b28ed3
        - ## Header2
          background-color:: red
        - ### Header3
          background-color:: yellow
        - #### Header4
          background-color:: green
        - ##### Header5
          background-color:: blue
        - ###### Header6
          background-color:: purple
        - ###### Header6 #.columns
          background-color:: pink
          id:: 644251cc-066c-4544-a01a-80b09d5c0b99
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
        -
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
        -
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
        -
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
        - #.columns
          id:: 644256ae-3c2c-4d15-9600-ffd55a766600
            - id:: 63b8e38c-738e-4056-a742-79e47d9b9051
              #+BEGIN_NOTE
              Note
              #+END_NOTE
            - #+BEGIN_PINNED
              Pinned
              #+END_PINNED
        - #.columns
            - #+BEGIN_TIP
              Tip
              #+END_TIP
            - #+BEGIN_IMPORTANT
              Important
              #+END_IMPORTANT
        - #.columns
            - #+BEGIN_CAUTION
              Caution
              #+END_CAUTION
            - #+BEGIN_WARNING
              Warning
              #+END_WARNING
        - ### Macros
            - before {{wrong macro}} after
            - before {{{wrong macro}}} after
            - before {{i f25f}} after
            - before {{theme-test-macro1}} after
            - before {{theme-test-macro2}} after
            - before {{theme-test-macro3}} after
            -
        - ### Embedding
            - Page:
              collapsed:: true
                - {{embed [[Theme test]]}}
                  id:: 644256ae-44c9-46d1-8222-ade14e052a5d
                - ((644256ae-44c9-46d1-8222-ade14e052a5d))
            - Block:
              id:: 635e191b-7e56-4997-b3ac-79eba758bd8d
                - {{embed ((634d5efa-2b06-402b-ad48-1de87fb2d770))}}
                  id:: 644256ae-0ce5-4aa4-a29c-b31a35911143
                - ((644256ae-0ce5-4aa4-a29c-b31a35911143))
            -
            -
            - block props: ((644256fa-887f-44a3-aa36-aca8ce520de0))
            - block props: ((9c8f2daa-09e8-40fd-b306-4a7f422a399c))
            -
            - ((63b8e38c-a943-4ba0-b8d7-ad704453e29e))
            - ((6423a937-76b6-4234-a772-9c42b88cacca))
            -
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
                - **[LABEL →](((63b8e38c-a943-4ba0-b8d7-ad704453e29e)))**
                - [**LABEL →**](((63b8e38c-a943-4ba0-b8d7-ad704453e29e)))
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
            -
            -
            - ((634d5d93-5e38-4ca0-9c7a-f42c8378158b))
            - ((644251cc-34dc-49a2-85cb-85c5c90074de))
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
            - first **line**
              id:: 64424b33-db00-4545-8676-896bebb9a5e9
              text
            - 1 ((64424b33-db00-4545-8676-896bebb9a5e9))
              id:: 64424b44-772f-4b60-abfb-b0e1232b9c60
            - 2 ((64424b44-772f-4b60-abfb-b0e1232b9c60))
              id:: 64424b4c-eb2d-4520-8193-dcddb01b8415
            - 3 ((64424b4c-eb2d-4520-8193-dcddb01b8415))
              id:: 64424b4e-b6b0-4ceb-9994-bd512f3d4579
            - 4 ((64424b4e-b6b0-4ceb-9994-bd512f3d4579))
              id:: 64424b4f-c13a-46f1-927f-90294d80c735
            - 5 ((64424b4f-c13a-46f1-927f-90294d80c735))
              id:: 64424b51-cb52-4487-9f03-4b04b0620f08
            - 6 ((64424b51-cb52-4487-9f03-4b04b0620f08))
              id:: 64424b53-314a-4c6d-93eb-8e9f3d78cdec
            - 7 ((64424b53-314a-4c6d-93eb-8e9f3d78cdec))
              id:: 64424b55-f5e7-4444-b5a8-48e10c42c06e
            -
            - r1 ((64424ba8-f435-47fa-b7eb-b911c3a5a3e4))
              id:: 64424b83-d11e-491f-b2d2-0536763bd8ad
            - r2 ((64424b83-d11e-491f-b2d2-0536763bd8ad))
              id:: 64424ba8-f435-47fa-b7eb-b911c3a5a3e4
        - ### Icons for properties
          collapsed:: true
            - Logseq
              tags:: "test"
              alias:: "test"
              file:: test
              file-path:: test
              template:: test
              template-including-parent:: test
            - Other #.columns
                - some-property:: test
                  tag:: icon test
                  label:: icon test
                  file-smth:: test
                  template-smth:: test
                  ref:: icon test
                  source:: icon test
                  author:: icon test
                  creator:: icon test
                  leading:: icon test
                  owner:: icon test
                  assignee:: icon test
                  who:: icon test
                  state:: icon test
                  status:: icon test
                  date:: icon test
                  date-smth:: icon test
                  start:: icon test
                  end:: icon test
                  day:: icon test
                  week:: icon test
                  month:: icon test
                  year:: icon test
                  when:: icon test
                  duration:: icon test
                  time:: icon test
                - color:: icon test
                  related:: icon test
                  url:: icon test
                  link:: icon test
                  text:: icon test
                  summary:: icon test
                  description:: icon test
                  comment:: icon test
                  note:: icon test
                  category:: icon test
                  topic:: icon test
                  area:: icon test
                  location:: icon test
                  place:: icon test
                  where:: icon test
                  format:: icon test
                  type:: icon test
                  size:: icon test
                  level:: icon test
                  isbn:: icon test
                  number:: icon test
                  task:: icon test
                  project:: icon test
                  price:: icon test
                  rating:: icon test
        - ### Other
          collapsed:: true
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
            - Number list #.numlist
                - item
                - item
                  collapsed:: true
                    - sub-item
                - item
            - Columns #.columns
                - first
                - second
                    - sub
        - ### Levels
          id:: 636ecf85-8100-4373-80d8-cbe9fa8aefb9
          collapsed:: true
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
