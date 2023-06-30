# Material design - components

Tags: UX design
관련 링크: https://m3.material.io/components
상태: In progress
작성 일자: 2022년 10월 31일 오후 2:46

# Material design - components

Components are interactive building blocks for creating a user interface. They can be organized into five categories based on their purpose: Action, containment, navigation, selection, and text input.

# Action

## Buttons

![There are five button styles in material 3](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled.png)

There are five button styles in material 3

![Untitled](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%201.png)

- All buttons have fully rounded corners
- Icons and labels now share the same color.
- Button text is in sentence case, no ALL CAPS
- Capitalize the first letter of the first word and proper nouns in button label text
- Don’t use two icons in the same button.
    
    ![Screenshot 2022-10-31 at 15.39.25.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-10-31_at_15.39.25.png)
    

## Floating Action Buttons

- Use a FAB for the most common or important action on a screen
    
    ![There are three sizes of floating action buttons: FAB, small FAB, and large FAB.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/unnamed.png)
    
    There are three sizes of floating action buttons: FAB, small FAB, and large FAB.
    
- The FAB appears in front of all other content on screen
- The FAB should persist on the screen when content is scrolling
- Icons in a FAB must be clear and understandable since these buttons do not have a text label

![Screenshot 2022-11-01 at 14.22.56.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-01_at_14.22.56.png)

![Screenshot 2022-11-01 at 14.24.28.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-01_at_14.24.28.png)

- Extended FABs can collapse into a FAB on scroll and expand on reaching the bottom of the view.
- [When tabs are present, the FAB should briefly disappear, then reappear when the new content moves into place. This shows that the FAB is not connected to any particular tab or destination.](https://m3.material.io/components/floating-action-button/guidelines#4dd3a071-5250-4b4b-97b8-78c7ca9e808f)
- The FAB can expand and adapt to any shape.
    
    
    [l5jnpuq1-Moving_Across_Tabs_DO_3P.mp4](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l5jnpuq1-Moving_Across_Tabs_DO_3P.mp4)
    
    [l0js5c2i-efab_ scrolling_3P.mp4](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l0js5c2i-efab__scrolling_3P.mp4)
    
    [l0a5htks-fab-primary-action.mp4](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l0a5htks-fab-primary-action.mp4)
    

## Extended Floating Action Buttons

- Extended FABs are the most visually prominent button.
- Use an extended FAB to provide persistent access to a primary action above long-scrolling surface content.
- Because it has room for both a text label and an icon, the extended FAB can be more effective where an icon alone might be too ambiguous.

![unnamed.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/unnamed%201.png)

1. Extended FAB with both icon and label text

2. Extended FAB without icon

![Screenshot 2022-11-02 at 12.20.21.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-02_at_12.20.21.png)

![Screenshot 2022-11-02 at 12.21.54.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-02_at_12.21.54.png)

![Screenshot 2022-11-02 at 12.22.24.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-02_at_12.22.24.png)

![Screenshot 2022-11-02 at 12.22.57.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-02_at_12.22.57.png)

![Screenshot 2022-11-02 at 12.24.19.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-02_at_12.24.19.png)

- animation
    
    
    [l6paf0gh-EFAB_appear_3P_2.mp4](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l6paf0gh-EFAB_appear_3P_2.mp4)
    
    [l5iqp2np-efab_switch_1P_2.mp4](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l5iqp2np-efab_switch_1P_2.mp4)
    
    [l6pafa18-EFAB_Transforming_3P_2.mp4](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l6pafa18-EFAB_Transforming_3P_2.mp4)
    
    [l5iqmku1-eFAB - Container transform - 3p.mp4](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l5iqmku1-eFAB_-_Container_transform_-_3p.mp4)
    

## Icon Buttons

- Use icon buttons when a compact button is required, such as in a toolbar or image list
    
    ![unnamed.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/unnamed%202.png)
    
    1. Standard icon button
    
    2. Contained icon button (including filled, filled tonal, and outlined styles)
    
- Icon buttons can take the form of a wide range of system icons
- Ensure the meaning of the icon is unambiguous
- On hover, include a tooltip that describes the button’s action, rather than the name of the icon itself
    
    ![l1m70y6i-icon_btn_selection_a_3P.gif](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l1m70y6i-icon_btn_selection_a_3P.gif)
    
- Use the outline-style icons to indicate an unselected state and a filled style to indicate selection
    
    ![l1m717rq-icon_btn_selection_b_3P.gif](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/l1m717rq-icon_btn_selection_b_3P.gif)
    

- placement
    
    
    ![Screenshot 2022-11-03 at 12.15.46.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-03_at_12.15.46.png)
    
    ![Screenshot 2022-11-03 at 12.15.58.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-03_at_12.15.58.png)
    
    ![Screenshot 2022-11-03 at 12.12.15.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-03_at_12.12.15.png)
    
- dos and don’ts
    
    ![Screen Recording 2022-11-03 at 12.19.51.gif](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screen_Recording_2022-11-03_at_12.19.51.gif)
    

## Segmented Buttons

Segmented buttons help people select options, switch views, or sort elements.

![A segmented button can help switch between viewing restaurant and bar options.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%202.png)

A segmented button can help switch between viewing restaurant and bar options.

![1. Single-select segmented button  | 2. Multi-select segmented button](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%203.png)

1. Single-select segmented button  | 2. Multi-select segmented button

![Optional check icon to indicate selected state](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%204.png)

Optional check icon to indicate selected state

![Screenshot 2022-11-07 at 14.57.29.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-07_at_14.57.29.png)

![Screenshot 2022-11-07 at 15.00.20.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-07_at_15.00.20.png)

![Screenshot 2022-11-07 at 15.00.28.png](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Screenshot_2022-11-07_at_15.00.28.png)

[Icons become checkmarks when selected in buttons that also use label text.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl519nuby-%5B3P%5D%20segmented-button-behavior.mp4?alt=media&token=a5834979-23cb-42e9-b6fd-05b510f6934a)

Icons become checkmarks when selected in buttons that also use label text.

# Communication

## Badges

Use badges with navigation items to convey dynamic information associated with that destination

[Small badge (on a navigation item) | Large badge (on a navigation item) | Large badge with max characters (on a navigation item)](https://lh3.googleusercontent.com/bJWl4TtT9yNTCfsCPsZ4xzduOm2kk9xyhiRfu2ZCpNMvGGkGgqShRAKNBpsxfrTFg0vJ9sw2nkfgndkfS5NDY9iSKDoHKo5Gl--O0QrUSvNF=s0)

Small badge (on a navigation item) | Large badge (on a navigation item) | Large badge with max characters (on a navigation item)

[In navigation bars, hide the badge once the destination has been selected.](https://lh3.googleusercontent.com/sWniiwDnJYwg6CSy2aNXFYZqflr8MHCQJUBqKts9U_sdhfPX9bFDTyf7dokV-LbQRmaeXEd4pXJW_K-HxQ17BN4hCxs6j_E1wA_sXbUH8Uk=s0)

In navigation bars, hide the badge once the destination has been selected.

[Don’t let the badge get cut off or collide with another element.](https://lh3.googleusercontent.com/yPLx3YgXp-usHMNhFQrs33NsBv0Jpz1lnlYgeiNoLCOpl7NaaVTbkSKvOaoXQjcnC00IhswGE8Bh2ewzNyj9C0rBae0zIyDewpXxpkCPILRI=s0)

Don’t let the badge get cut off or collide with another element.

[Avoid using a large badge when it might overlap with a trailing element. Either place it at the ending edge of the lockup or use a small badge instead.](https://lh3.googleusercontent.com/DBABe9WStgE3YbZPf0yvO5TSjGkEMEBNBB6WiV89yH0MpGyq8FNuwG3h7Rrq78u_zkd5y3vswob4yPXaSdoPk6oOQL1Boh1VV6O7mkXnwX8=s0)

Avoid using a large badge when it might overlap with a trailing element. Either place it at the ending edge of the lockup or use a small badge instead.

![Badges have fixed positions. Don’t change the position of the badge arbitrarily or place the badge over the icon.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%205.png)

Badges have fixed positions. Don’t change the position of the badge arbitrarily or place the badge over the icon.

[Avoid using custom color mappings for the badge container and label text. They may not meet accessibility requirements.](https://lh3.googleusercontent.com/X1OaGXtq2nwatHa69ZCxJQmLLuLS5tRQvlc5-cv1ayoHKEdG_Ru_CdSL6UOOJx29uuD3gcYt49O23zQ7mADdlnOhqX-DKZaT2eLHtvlehbRr=s0)

Avoid using custom color mappings for the badge container and label text. They may not meet accessibility requirements.

## Progress Indicators

Progress indicators should be applied to all instances of a process (such as loading) in a consistent format (linear or circular)

![There are two types of progress indicators: Linear and circular.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%206.png)

There are two types of progress indicators: Linear and circular.

![Determinate linear progress indicator](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/ezgif-2-55a2ffe1cf.gif)

Determinate linear progress indicator

![Indeterminate linear progress indicator](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/ezgif-2-be3c943737.gif)

Indeterminate linear progress indicator

## Snackbars

Dismissive snackbars appear temporarily, and disappear on their own without requiring user input. Non-dismissive snackbars persist until the user takes an action or selects the close affordance.

- Only one snackbar may be displayed at a time.
- A snackbar can contain a single action. "Dismiss" or "cancel" actions are optional.
- On mobile, the text label can contain up to two lines of text.
- Containers should be completely opaque, so that text labels remain legible.

![Don’t use icons in snackbars. If your message needs an icon, consider using a different component.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%207.png)

Don’t use icons in snackbars. If your message needs an icon, consider using a different component.

![An app can apply slight transparency to the container background, as long as text remains clearly legible.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%208.png)

An app can apply slight transparency to the container background, as long as text remains clearly legible.

![To distinguish the action from the text label, text buttons should display colored text.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%209.png)

To distinguish the action from the text label, text buttons should display colored text.

![Don’t use a filled or elevated button in a snackbar, as it draws too much attention.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2010.png)

Don’t use a filled or elevated button in a snackbar, as it draws too much attention.

![If an action is long, the button can be displayed on a third line.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2011.png)

If an action is long, the button can be displayed on a third line.

![A dismiss action is unnecessary, as snackbar disappears on their own by default.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2012.png)

A dismiss action is unnecessary, as snackbar disappears on their own by default.

![Avoid significantly altering the shape of a snackbar container.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2013.png)

Avoid significantly altering the shape of a snackbar container.

![Avoid placing snackbars in front of navigation components.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2014.png)

Avoid placing snackbars in front of navigation components.

![Don’t place a snackbar behind a FAB.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2015.png)

Don’t place a snackbar behind a FAB.

![Don’t place a snackbar in front of a FAB.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2016.png)

Don’t place a snackbar in front of a FAB.

![Snackbar above a FAB.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2017.png)

Snackbar above a FAB.

[Don’t stack snackbars on top of one another.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl7qbqg9s-3p-snackbars-behavior-don_t.mp4?alt=media&token=646b3186-f507-4d98-a1e6-90a6b9c48695)

Don’t stack snackbars on top of one another.

[Don’t animate other components along with snackbar animations, such as the floating action button.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl7qbrszo-3p-snackbars-behavior-dont-2.mp4?alt=media&token=cb43d1bb-1be5-4943-b80c-122470c4a26c)

Don’t animate other components along with snackbar animations, such as the floating action button.

# Containment

Containment components hold information and actions – including other components like buttons, menus, or chips.

## Bottom sheets

Bottom sheets display content that complements the screen’s primary content. They can be dismissed in order to interact with the underlying content.

![There are two types of bottom sheets: ① standard and ② modal. Modal bottom sheets are above a scrim while standard bottom sheets don't have a scrim. Besides this, both types of bottom sheets have the same specs.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2018.png)

There are two types of bottom sheets: ① standard and ② modal. Modal bottom sheets are above a scrim while standard bottom sheets don't have a scrim. Besides this, both types of bottom sheets have the same specs.

## Cards

Use a card to display content and actions on a single topic

![There are three types of cards: ① elevated, ② filled, and ③ outlined.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2019.png)

There are three types of cards: ① elevated, ② filled, and ③ outlined.

[Cards use a container transform transition pattern to reveal additional content.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0d2qjpe-cards-expand_3P_2.mp4?alt=media&token=f6252b7c-cb3d-4c91-9701-13b9bf9f482d)

Cards use a container transform transition pattern to reveal additional content.

[Cards can use a forward and backward transition pattern to navigate between screens.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl5joquou-Cards%20-%20Forward%20and%20backward%20-%203P.mp4?alt=media&token=bf9b389b-77df-40cd-ba28-8d05bfaeb05d)

Cards can use a forward and backward transition pattern to navigate between screens.

![Cards can contain icon buttons like stars to rate content.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2020.png)

Cards can contain icon buttons like stars to rate content.

![Cards can contain choice chips within the action area.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2021.png)

Cards can contain choice chips within the action area.

![Cards can contain a slider control within the action area.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2022.png)

Cards can contain a slider control within the action area.

![Multiple cards can be grouped into collections with a shared resting elevation.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2023.png)

Multiple cards can be grouped into collections with a shared resting elevation.

[Cards can be shown in a vertical list.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0d1zeju-cards_vertical_list_nosparkle_3P.mp4?alt=media&token=dcb21e89-f041-4999-877e-85a10962c0b5)

Cards can be shown in a vertical list.

[Cards displayed together in a horizontal row or carousel.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0v8qhs7-cards_carousel_3P_1.mp4?alt=media&token=bde00407-78d3-4d1c-9cb6-a58729bd257d)

Cards displayed together in a horizontal row or carousel.

[Adjust component layout so content remains the main focus on large screens.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0d22chv-cards-swapping_3P_1.mp4?alt=media&token=5574195f-e203-4ee6-a85d-02e4dff005fe)

Adjust component layout so content remains the main focus on large screens.

![Example of the same card with two different orientations and element positioning.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2024.png)

Example of the same card with two different orientations and element positioning.

[A card should only have 1 swipe action assigned to it.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0d24rvo-cards-swipe_do_3P.mp4?alt=media&token=2f1faebb-e159-4b6c-a324-87257ae596cc)

A card should only have 1 swipe action assigned to it.

[When moving a card, increase its elevation](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0d27q3j-cards-move_do_3P_1.mp4?alt=media&token=246075d0-1e2f-4fe0-b9b8-1f59aadecff5)

When moving a card, increase its elevation

[On a mobile device, cards can expand to reveal more content. Content within cards doesn’t scroll.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0d2gcqf-cards-scrolling_do.mp4?alt=media&token=051d6c03-c436-4d86-9084-ae3bbc3f0528)

On a mobile device, cards can expand to reveal more content. Content within cards doesn’t scroll.

[On a desktop device, card content can expand and scroll within a card.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0d2oom6-cards-desktop_scroll_3P.mp4?alt=media&token=e57dba99-5a1b-433e-ba5e-ca1ee7824d0e)

On a desktop device, card content can expand and scroll within a card.

## Dialogs

![There are two types of dialogs: basic and full-screen.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2025.png)

There are two types of dialogs: basic and full-screen.

![Don’t use dialogs for low- or medium-priority information. Also, dialog can be custom positioned on the right side of the screen for a more ergonomic experience.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2026.png)

Don’t use dialogs for low- or medium-priority information. Also, dialog can be custom positioned on the right side of the screen for a more ergonomic experience.

[Full-screen dialogs contain actions that require a series of tasks to complete.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl0v3n834-Dialogs_Modal_3P_2.mp4?alt=media&token=48cffc7a-0431-4ae6-94b9-665a01829bc2)

Full-screen dialogs contain actions that require a series of tasks to complete.

![Basic dialogs require the user to take action before it will close.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2027.png)

Basic dialogs require the user to take action before it will close.

![Basic dialogs can give users the ability to provide confirmation of a choice before committing to it.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2028.png)

Basic dialogs can give users the ability to provide confirmation of a choice before committing to it.

![Date picker dialogs allow users to tap a date, then confirm it by tapping “OK.”](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2029.png)

Date picker dialogs allow users to tap a date, then confirm it by tapping “OK.”

![Time picker dialogs allow users to move the clock hand and then confirm by tapping “OK.”](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2030.png)

Time picker dialogs allow users to move the clock hand and then confirm by tapping “OK.”

![For headlines, avoid apologies (Sorry for the interruption), extra alarm (Warning!), or ambiguity (Are you sure?](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2031.png)

For headlines, avoid apologies (Sorry for the interruption), extra alarm (Warning!), or ambiguity (Are you sure?

![Avoid placing long headlines in a full-screen dialog’s top app bar (1), as the truncated text may lead to misunderstanding.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2032.png)

Avoid placing long headlines in a full-screen dialog’s top app bar (1), as the truncated text may lead to misunderstanding.

![Don’t place dismissive actions (1) to the right of confirming actions. Instead, place them to the left of confirming actions.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2033.png)

Don’t place dismissive actions (1) to the right of confirming actions. Instead, place them to the left of confirming actions.

![Stacked buttons accommodate longer button text but take up more room. Confirming actions appear above dismissive actions.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2034.png)

Stacked buttons accommodate longer button text but take up more room. Confirming actions appear above dismissive actions.

![Don’t use the third button other than the confirming button and the dismissive button. The “Learn more” action (1) navigates away from this dialog, potentially leaving it in an indeterminate state.](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2035.png)

Don’t use the third button other than the confirming button and the dismissive button. The “Learn more” action (1) navigates away from this dialog, potentially leaving it in an indeterminate state.

[Dialogs appear without warning, entering and exiting the screen in a fade-transition pattern.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl5jnvi3y-Dialog%20-%20Enter%20and%20exit%20-%203P.mp4?alt=media&token=b76e88e2-438f-4b04-b4c8-c5cf3ab26a78)

Dialogs appear without warning, entering and exiting the screen in a fade-transition pattern.

## Divider

- A divider is a thin line that groups content in lists and containers.
- Dividers can reinforce tapability, such as when used to separate list items or define tappable regions in an accordion.

![Untitled](Material%20design%20-%20components%204d9549132e6d4c31bdc72e7e26b6992a/Untitled%2036.png)