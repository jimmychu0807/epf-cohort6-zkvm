## Key date
hookathon starts: May 25
hookathon ends: Jun 11

# Workshop

src: https://github.com/AtriumAcademy/workshops

## workshop-00: Orientation

UHI9 Orientation [slides](https://docs.google.com/presentation/d/1z4Ve3JQ3R-rK66yB7EnUadkA-BddzXXdSDMXCnGLyn4/edit?slide=id.g339cc4aa22c_0_169#slide=id.g339cc4aa22c_0_169)

overall [course schedule](https://learn.atrium.academy/course/4b6c25df-f4c8-4b92-ab38-a930284d237e/course-introduction/schedule)

## workshop-01: Course & Technical Introduction

[slides](https://docs.google.com/presentation/d/16Vuudcl4DvERRFTCAWHOchVKYJd08_p7oX43VMlkH_0/edit?slide=id.g2cb6f1d4e5b_0_214#slide=id.g2cb6f1d4e5b_0_214)
completed

## workshop-02: Ticks and Q64.96 Numbers

[slides](https://docs.google.com/presentation/d/1wLms8FsfRnMn7mQ2CR02XHHwrsUaSUwg7X7WnYBhVHs/edit?slide=id.g2cd44810d93_1_26#slide=id.g2cd44810d93_1_26)
completed

## workshop-03: Building your first hook

[slides](https://docs.google.com/presentation/d/1AYd1bXbgcU7DMCQzCTFDPOpAfqLJpC99dlKV1FyyAmU/edit?slide=id.g2cb6f1d4e5b_0_118#slide=id.g2cb6f1d4e5b_0_118)
completed

## Workshop 4: Testing and Deploying a Hook

[slides](https://docs.google.com/presentation/d/1dM6li59o0gfzixgEHPZJzaUi6wdpIEx8N26ZaIWDp7s/edit?slide=id.g1f56a667a16_0_100#slide=id.g1f56a667a16_0_100)
[lectures](https://learn.atrium.academy/course/4b6c25df-f4c8-4b92-ab38-a930284d237e/testing-and-deploying/testing)

## Workshop 5: Dynamic Fees

[slides](https://docs.google.com/presentation/d/1AOxwU7f3ao5aGYQyhy9nYjvvhr_beb6HmZM_b9xx1xc/edit?slide=id.g1f56a667a16_0_100#slide=id.g1f56a667a16_0_100)
[lectures](https://learn.atrium.academy/course/4b6c25df-f4c8-4b92-ab38-a930284d237e/dynamic-fees)

## Workshop 6: Dynamic Fees: Nezlobin's Directional Fee

Return delta hook

[slides](https://docs.google.com/presentation/d/1JafFlLSKEzhDpbN7rPbODokni0MRQm5-Knw4jS8FOH4/edit?slide=id.g1f56a667a16_0_100#slide=id.g1f56a667a16_0_100)
[lectures](https://learn.atrium.academy/course/4b6c25df-f4c8-4b92-ab38-a930284d237e/nezlobin/nezlobin)

## Workshop 7: Reactive Network Guest Workshop

## Workshop 7: Limit Orders Pt. 1

## Workshop 8: Limit Orders Pt. 2

## Workshop 9 & 10: Guest Lecture

## Workshop 11: MEV: Coincidence of Wants

## Hook Security
- [Cyfrin hook security deep dive](https://www.cyfrin.io/blog/uniswap-v4-hooks-security-deep-dive)

## WOrkshop 12: Periphery: Swap + Bridge

# Quick Ideas

- use concentrated liquidity, but use hook to adjust dynamically. So it is capital efficient.
- range order, to limit order, after crossing the range, withdraw immediately. So it doesn't get unfilled when the price go reversed and recross the price point
- kyc'ed pools?

# Ref
- Atrium Academy:
  https://learn.atrium.academy/course/4b6c25df-f4c8-4b92-ab38-a930284d237e/intro

- hook directory:
  - atrium maintained: https://atriumacademy.notion.site/hook-directory
  - hook atlas: https://hookatlas.com/hooks

- Request for Hook:
  https://atriumacademy.notion.site/atrium-academy-request-for-hooks

# Notes on ecosystem

## uniswap SDK
- there is a uniswap SDK v4 - in ts format
  - https://developers.uniswap.org/docs/sdks/v4/overview
- and then a community SDK: 
  - https://developers.uniswap.org/docs/community/tooling/community-sdk
- there is a openzepellin uniswap hooks: https://docs.openzeppelin.com/uniswap-hooks


## Template to build v4 hooks

- https://developers.uniswap.org/docs/community/tooling/v4-template

## Hook discovery & brainstorming

- https://hookatlas.com/hooks

# Pendle Finance Study

- youtube channel: https://www.youtube.com/@pendle_fi/videos
