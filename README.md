# wai-aria test 공간

## wai-aria-practices
https://www.w3.org/TR/wai-aria-practices/examples/

## tutorials
https://www.w3.org/WAI/tutorials/menus/structure/

## ARIA in HTML
- https://www.w3.org/TR/html-aria/


# Using ARIA: Roles, states, and properties
# role
## widget-roles
- button
- checkbox
- gridcell
- link
- menuitem
- menuitemcheckbox
- menuitemradio
- option
- progressbar (실시간 진행률)
- radio
- scrollbar
- searchbox
- separator
- slider
- spainbutton
- switch
- tab
- tabpanel
- textbox
- treeitem

## composit roles
- combobox
- grid (including row, gridcell, rowheader, columnheader roles)
- listbox (includeing option role)
- menu
- menubar 
- radiogroup (radio role)
- tree
- treegrid

## Document structure roles
- application
- article
- cell
- columnheader
- definition
- directory
- document
- feed
- figure
- group
- heading
- img
- list
- listitem 
- math 
- none
- note
- presentation
- row
- rowgroup
- rowheader
- separator
- table
- term
- textbox
- toolbar
- tooltip

## Landmark roles
- banner
- complementary
- contnetinfo
- form
- main
- navigation
- region
- search

## Live Region roles
- alert
- log
- marquee
- status
- timer 

## Window roles
- alertdialog 
- dialog

# States and properties 
## Widget attributes
- aria-autocomplete
- aria-checked
- aria-current
- aria-disabled
- aria-errormessage
- aria-expanded
- aria-haspopup
- aria-hidden
- aria-invaild
- aria-label
- aria-modal
- aira-multilin
- aria-mulitselectable
- aria-orientation
- aria-placeholder
- aria-pressed
- arai-readonly
- aria-required
- aria-selected
- aria-sort
- aria-valuemax
- aria-valuemin
- aria-valuenow
- aria-valuetext

## Live region attributes
- aria-live
- aria-relevant
- aria-atomic
- aria-busy

## Drag &b drop attributes
- aria-dropeffect
- aria-dragged

## Relationship attributes
- aria-activedescendant
- aria-colcount
- aria-colindex
- aria-colspan
- aria-controls
- aria-describedby
- aria-details
- aria-errormessage 
- aria-flowto
- aria-labelledby
- aria-owns
- aria-posinset
- aria-rowcount
- aria-rowindex
- aira-rowspan
- aria-setsize 


# wai-aria 1.2 추가 
## roles

- blockquote
- superscript / subscript
- code 
- caption : table, grid, figure 가진 태그에 사용. 
- meter (HTML5에서 고정된 수치의 값을 표시하기 위한 스칼라 수치 막대를 추가하는 <meter> 태그를 이제 role=”meter”를 통해 제공)
  * meter 태그에는 min, max를 통해 최솟값과 최댓값을 정하며, value 속성으로 수치를 제공. role=”meter"에는 이것들을 대체하는 aria-valuemin, aria-valuemax를 제공해야 함. arai-valuenow 현재값 제공. 

- insertion , deletion (ins(삽입) / del(삭제) 태그 대체. )
- time 
- paragraph (<p> 요소를 대체하는 WAI-ARIA 역할인 role=”paragraph”)
- generic (시멘틱 의미가 없는 요소. div나 span에 해당하는 제네릭 역할, role="generic"이 추가 )

* wai-aria 1.2 추가된 role은 모두 html 표준 엘리먼트로 존재. 
표준 엘리먼트 사용을 권장. 

















