# SUPER ESELATOR Ver. 4.5.5
<img width="481" height="590" alt="image" src="https://github.com/user-attachments/assets/0ef4977b-aec5-4dd0-8ff7-708d6a73af8a" />

<img width="354" height="554" alt="image" src="https://github.com/user-attachments/assets/688e55d8-714f-4a02-a2c5-914cc6465bb9" />
<img width="334" height="287" alt="image" src="https://github.com/user-attachments/assets/631e58fd-3420-4601-ab4c-0c82794e8ad7" />

## Update Details / 更新内容

### English
- Added a shortcut key reference table
- Increased the number of FX types
  - Added tape wobble and lo-fi degradation effects
- Adjusted preset sound volumes
- Added 7th and 9th chord options to the chord buttons
- Added a strum function to the chord buttons

### 日本語
- キーのショートカット表を追加
- FX種類の増加
  - テープ揺れ・ローファイ劣化表現の追加
- プリセット音色の音量調整
- コードボタンに7th/9thを追加
- コードボタンにストラム機能を追加

---

## SUPER ESELATOR Overview

SUPER ESELATOR is a retro-style Web Audio performance tool for touch screens, keyboards, gamepads, and mobile devices.

It includes:

- Live sound performance
- Loop recording and overdubbing
- Chord pads
- Deck-based sound switching
- Real-time FX
- WAV recording
- Project save/load

---

## 1. Deck System

The app has four independent decks:

- DECK A
- DECK B
- DECK C
- DECK D

Each deck can hold its own preset sound, mute state, and playback behavior.

### Use cases
- Switch between different instruments quickly
- Keep multiple sound roles available at once
- Play one sound set while preparing another
- Save different setups into a project

### Deck controls
- Select a deck
- Mute / unmute a deck
- Change the preset assigned to each deck
- Use different sounds on different decks during performance

---

## 2. Preset Sound Engine

Each deck can be assigned a preset sound from a large preset library.

### Preset categories
- Bass
- Lead
- Chord / Pad
- Piano
- SFX / FX
- Drum Kits
- Ambient / Nature

### Preset types
The engine includes many sound behaviors, such as:

- Synth waves
- Chord stacks
- Piano models
- Drum kit voices
- Ambient noise textures
- Effect-style SFX
- Arpeggio or laser-type sounds

### Preset volume
Each preset can have its own volume multiplier, so you can balance loudness per sound independently.

---

## 3. Touch Pad Performance

The large screen area acts as the main performance pad.

### Touch pad behavior
- Horizontal position controls pitch or scale note
- Vertical position controls filter cutoff
- Different touch positions trigger different tones
- Works like a performance instrument

### Visual feedback
- Grid lines show note zones
- Note names are displayed across the pad
- Particles appear when notes are triggered
- A looping time bar shows playback position
- The display changes with octave shift and scale selection

### Touch pad role
This is the main live-play area for:

- Melody playing
- Drum triggering
- Performance gestures
- Loop recording input

---

## 4. Scale and Key System

You can choose both:

- Key
- Scale / Mode

### Supported scale types
- Chromatic
- Major
- Natural Minor
- Pentatonic Major
- Pentatonic Minor
- Blues
- Dorian
- Phrygian
- Lydian
- Mixolydian
- Locrian
- Harmonic Minor
- Melodic Minor
- Japanese scales
- Arabic / Double Harmonic
- Whole Tone
- Diminished
- Chiptune Triad Arp

### Why this is useful
- Quickly change musical mood
- Match chords and melody to a key
- Create different musical flavors from the same pad layout

---

## 5. Octave Shift

The pad system supports octave shifting.

### Features
- Shift pitch up or down
- Affects touch pad notes and chord pads
- Useful for switching between bass ranges and lead ranges

### Behavior
- Octave display updates on screen
- Touch pad theme changes visually depending on octave
- The pad stays usable while transposed

---

## 6. Chord Pads

There are five chord pads under the touch pad.

### Chord pad functions
- Trigger harmony chords instantly
- Each pad has a scale-aware chord name
- Pads follow the current key and scale
- Can generate triads, 7th chords, or 9th chords

### Chord extension modes
- TRIAD
- 7th
- 9th

### What chord pads are for
- Building harmonic progressions
- Playing backing chords live
- Creating chord loops
- Quickly changing the harmony of a performance

---

## 7. Strum Mode

Chord pads can be played in strum style.

### Strum mode features
- Notes in the chord are triggered one by one
- Low note to high note order
- Adjustable gap time between notes

### Controls
- Turn strum mode on or off
- Adjust strum interval
- Adjust chord length

### Why this matters
It creates a more human, guitar-like or keyboard-like chord feel instead of all notes sounding exactly at once.

---

## 8. Loop Recording

The app supports live loop recording.

### Recording states
- STANDBY
- REC FREE
- WAIT HEAD
- PLAYING
- OVERDUB

### Loop recording features
- Record your performance into a loop
- Play back the recorded material continuously
- Add overdubs while the loop is running
- Use touch pad notes and chord pads in the loop
- Keep timing data for each note

### Timing behavior
The app stores:

- Note time offsets
- Duration
- Deck assignment
- Preset ID
- Chord grouping
- Drum type if used

This makes loop playback accurate and flexible.

---

## 9. Overdub Support

You can layer new notes on top of an existing loop.

### Overdub lets you
- Add extra melody lines
- Add chord changes later
- Fill in percussion or accents
- Build arrangements step by step

---

## 10. Undo

The `UNDO` function restores the previous loop state.

### Undo behavior
- Reverts the latest recording change
- Works after recording, overdubbing, and note edits
- Can restore the previous musical state without clearing everything

### Use cases
- Remove a bad take
- Roll back an accidental overdub
- Recover from a mistaken edit

---

## 11. Clear Active Deck

The `CLEAR` function removes notes only for the currently selected deck.

### Clear behavior
- Deletes all notes assigned to the active deck
- Leaves other decks intact
- Useful for performance cleanup
- Safer than clearing the whole project

---

## 12. Select / Double Sequence

The `SEL` function duplicates the current loop material.

### What it does
- Duplicates the recorded sequence
- Doubles the loop length
- Keeps the musical content aligned
- Useful for extending song structure

### Performance use
This is ideal for:

- Quickly making a longer arrangement
- Repeating a section
- Building a full song form from a short loop

---

## 13. Start / Stop Playback

The `START` button controls loop playback.

### Behavior
- Start playback from the loop
- Stop playback cleanly
- Resume if needed
- Keeps loop timing and notes in sync

---

## 14. FX Engine

SUPER ESELATOR includes a master FX engine.

### FX types
- Hall Reverb
- Echo Delay
- Lowpass Filter
- Delay + Filter
- Tape Wobble
- Tape Wobble + Filter
- Lo-Fi Cassette

### FX controls
- Global FX on/off
- FX type selection
- Two main XY-linked parameters
- Extra per-FX controls

### FX behavior
The engine affects live audio output in real time and can change the tone dramatically.

---

## 15. XY FX Pad

There is a dedicated XY control pad for effects.

### XY pad features
- X-axis controls one parameter
- Y-axis controls another parameter
- Visual pointer shows the current position
- Real-time parameter movement

### Why it is useful
- Fast hands-on effect control
- Good for live performance
- Easier than using only sliders

---

## 16. FX Extra Parameters

Each FX type has its own detailed parameters.

### Examples
- Reverb: pre-delay, decay, damping, size, mix
- Delay: time, feedback, tone, mix
- Filter: cutoff, resonance, drive, mix
- Tape effects: wow rate, wow depth, delay time, feedback, cutoff
- Lo-fi: wobble, dust, drive, cutoff, noise

### Purpose
These parameters let you shape the sound more precisely, beyond the main XY controls.

---

## 17. Deck Mute Controls

Each deck can be muted independently.

### Mute behavior
- Silences a deck’s output
- Does not delete notes
- Can be toggled live during playback

### Use cases
- Drop instruments out
- Isolate a specific part
- Create arrangement changes in real time

---

## 18. WAV Recording

The app can record the final audio output as a WAV file.

### WAV recording features
- Records the full master output
- Captures live performance and FX
- Converts the recorded stream into WAV
- Allows audio export at the end of a session

### Notes
- On some browsers, especially in-app browsers, download behavior may be limited
- Safari usually works more reliably on iPhone

---

## 19. Project Save / Load

You can save and reload your entire setup as a JSON project.

### Saved project includes
- Current key
- Current scale
- Active deck
- Deck presets
- Deck mute states
- FX state and parameters
- Preset volume multipliers
- Chord settings
- Loop data
- Recorded notes

### Why this is useful
- Restore a performance later
- Keep your setup portable
- Share sessions or continue editing after reloading

---

## 20. Keyboard Support

The app supports keyboard performance and control.

### Common keyboard functions
- `1` - `4`: select decks
- `Shift` + `1` - `4`: mute decks
- `5` - `9`: chord pads
- `A S D F G H J K`: touch pad notes
- `E`: FX on/off
- `R`: record / arm / overdub
- `U`: undo
- `C`: clear active deck
- `Space`: play / stop
- `Z`: previous sound
- `X`: next sound
- `Q`: octave down
- `W`: octave up

---

## 21. Gamepad Support

Gamepad control is also supported.

### Common gamepad functions
- `R`: record / arm / overdub
- `START` + `L`: play / stop
- `SELECT` + `L` / `R`: deck switching
- `SELECT` + `Y`: FX toggle
- `SELECT` + `X`: sequence double
- `SELECT` + `A`: undo
- `SELECT` + `B`: clear active deck
- `L` + directions: chord pads
- `A` / `B` / `X` / `Y`: touch pad performance
- `START` + directions: sound and octave controls

### Why gamepad support matters
- Better for hands-on live performance
- Easier on mobile setups with controllers
- Good for arcade-style playing

---

## 22. Mobile and Browser Compatibility

The app is designed with mobile and touch-first use in mind.

### Mobile-friendly features
- Touchpad gestures
- Large on-screen buttons
- No pinch zoom
- iPhone support
- Gamepad support on compatible browsers

### Browser note
Some in-app browsers, especially Instagram, may limit file saving.  
Safari is usually the best choice for recording and export.

---

## 23. Visual Feedback and UI Design

The interface is styled like a retro game console.

### Visual elements
- Glowing LED indicators
- Scanline-style screen effect
- Deck status highlights
- Active button feedback
- Live waveform-style or grid-style display elements

### Why this matters
It makes the app feel like a playable instrument, not just a music utility.

---

## 24. Performance-Oriented Design

The whole system is meant for live use.

### Designed for
- Quick switching
- Fast recording
- Improvisation
- Real-time editing
- Stage-like performance flow
```
## 更新内容

- キーのショートカット表を追加
- FX種類を増加
  - テープ揺れ・ローファイ劣化表現を追加
- プリセット音色の音量を調整
- コードボタンに 7th / 9th を追加
- コードボタンにストラム機能を追加

---

## SUPER ESELATOR とは

`SUPER ESELATOR` は、タッチ操作・キーボード・ゲームパッドで演奏できる、レトロ風の Web 音楽パフォーマンスツールです。

主な機能:

- リアルタイム演奏
- ループ録音
- オーバーダブ
- コード演奏
- 音色切り替え
- FX操作
- WAV録音
- プロジェクト保存 / 読み込み

---

## 1. デッキシステム

`DECK A` 〜 `DECK D` の4つのデッキがあります。  
各デッキごとに別々の音色を割り当てられます。

### できること
- 複数の音色を使い分ける
- 演奏中に別デッキへ切り替える
- デッキごとにミュートできる
- 保存データにもデッキ情報を保持できる

### 用途
- ベース、ピアノ、コード、SE などを分けて使う
- 曲の役割ごとに音色を整理する
- ライブ演奏で瞬時に音を切り替える

---

## 2. プリセット音色エンジン

各デッキには、豊富なプリセット音色を割り当てられます。

### 主なカテゴリ
- Bass
- Lead
- Chord / Pad
- Piano
- SFX / FX
- Drum Kits
- Ambient / Nature

### 音色の種類
- シンセ波形
- コード音色
- ピアノ系
- ドラムキット
- ノイズ系アンビエント
- 効果音系 SE
- アルペジオ系

### 音量調整
プリセットごとに音量倍率を設定できるので、音のバランスを調整しやすいです。

---

## 3. タッチパッド演奏

中央の大きな画面が、メインの演奏パッドです。

### 動作
- 横位置で音程やスケールの音を選ぶ
- 縦位置でフィルターのかかり具合を変える
- 触った位置に応じて音が鳴る

### できること
- メロディ演奏
- ドラム演奏
- ノート入力
- ライブパフォーマンス

### 表示
- グリッド線
- 音名表示
- パーティクル表示
- ループ再生バー
- オクターブ変化に応じた見た目の変化

---

## 4. スケールとキー

`Key` と `Scale / Mode` を選べます。

### スケール例
- Chromatic
- Major
- Minor
- Pentatonic Major
- Pentatonic Minor
- Blues
- Dorian
- Phrygian
- Lydian
- Mixolydian
- Locrian
- Harmonic Minor
- Melodic Minor
- 日本の音階
- Arabic / Double Harmonic
- Whole Tone
- Diminished
- Chiptune系

### できること
- 曲調を一気に変えられる
- コードとメロディの雰囲気を整えられる
- 同じ配置でも別の音楽に聴こえる

---

## 5. オクターブシフト

音程を上下にずらせます。

### 特徴
- タッチパッドやコードパッドの音程に反映
- ベース向け、リード向けに切り替えやすい
- 画面表示も変化する

### 用途
- 低音域でベースを鳴らす
- 高音域でリードを鳴らす
- 演奏中の音域変更

---

## 6. コードパッド

タッチパッド下に5つのコードパッドがあります。

### 機能
- すぐに和音を鳴らせる
- スケールに合わせてコード名が変わる
- `TRIAD`、`7th`、`9th` に切り替え可能

### 用途
- コード進行作成
- 伴奏
- ループに和音を加える
- ライブでの即興和声

---

## 7. ストラムモード

コードを一斉発音ではなく、順番に鳴らせます。

### できること
- 低音から高音へ順番に鳴らす
- ギターのような自然なアルペジオ感
- 音の間隔を調整できる

### 設定
- ストラム ON / OFF
- 発音間隔
- コード長さ

---

## 8. ループ録音

演奏をループとして記録できます。

### ループ機能
- 演奏した音を録音
- 再生しながら繰り返す
- ループ中にさらに追加録音できる
- タッチパッドもコードパッドも記録可能

### 録音状態
- `STANDBY`
- `REC FREE`
- `WAIT HEAD`
- `PLAYING`
- `OVERDUB`

### 記録される内容
- 発音時刻
- 音長
- デッキ情報
- プリセット ID
- コードグループ
- ドラム種別

---

## 9. オーバーダブ

既存のループに新しい音を重ねられます。

### できること
- メロディ追加
- コード追加
- リズム追加
- 少しずつ曲を育てる

---

## 10. Undo

直前の変更を元に戻せます。

### できること
- 録音ミスを取り消す
- 誤って追加した音を戻す
- ひとつ前の状態へ復帰

---

## 11. Clear Active Deck

今選んでいるデッキの音だけを消せます。

### 特徴
- アクティブなデッキだけ削除
- 他のデッキは残る
- ループ全消去より安全

---

## 12. SEL / Sequence Double

録音したシーケンスを複製します。

### できること
- ループ全体を2倍にする
- 同じフレーズを繰り返す
- 曲の構成を広げる

### 用途
- イントロから展開へつなげる
- 短いフレーズを長くする
- 曲の盛り上げに使う

---

## 13. START / Stop

ループ再生の開始と停止を行います。

### 動作
- 再生開始
- 停止
- ループの同期再開

---

## 14. FXエンジン

マスターFXを搭載しています。

### FX種類
- Hall Reverb
- Echo Delay
- Lowpass Filter
- Delay + Filter
- Tape Wobble
- Tape Wobble + Filter
- Lo-Fi Cassette

### 操作
- FX ON / OFF
- FXタイプ変更
- XYパッドでの制御
- 詳細パラメータ調整

### 役割
- 音全体の空間感を変える
- 音をローファイ化する
- エコーや濾波をかける

---

## 15. XY FXパッド

FXを直感的に操作できるタッチパッドです。

### 特徴
- X軸とY軸で2つのパラメータを同時制御
- 現在位置を画面上で可視化
- リアルタイムで変化する

---

## 16. FXの追加パラメータ

FXタイプごとに細かい設定があります。

### 例
- Reverb: pre-delay, decay, damping, size, mix
- Delay: time, feedback, tone, mix
- Filter: cutoff, resonance, drive, mix
- Tape系: wow rate, wow depth, delay time, feedback, cutoff
- Lo-fi: wobble, dust, drive, cutoff, noise

---

## 17. デッキミュート

各デッキを個別にミュートできます。

### 用途
- 一時的に音を消す
- 伴奏の一部だけ止める
- ライブ中の構成変更

---

## 18. WAV録音

最終出力をWAVファイルとして録音できます。

### 機能
- マスター出力を録音
- FX込みで保存可能
- WAVとしてダウンロード
- 演奏結果の書き出しに便利

### 注意
- Instagram内ブラウザなどでは保存に制限があることがあります
- iPhoneではSafariの方が安定しやすいです

---

## 19. プロジェクト保存 / 読み込み

現在の設定やループをJSONとして保存・復元できます。

### 保存される内容
- キー
- スケール
- アクティブデッキ
- 各デッキのプリセット
- ミュート状態
- FX設定
- プリセット音量倍率
- コード設定
- ループデータ
- 録音ノート

### 用途
- 作業の再開
- セットアップの保存
- 別端末への移動

---

## 20. キーボード操作

キーボードでも演奏や制御ができます。

### 主な割り当て
- `1 - 4`: デッキ選択
- `Shift + 1 - 4`: デッキミュート
- `5 - 9`: コードパッド
- `A S D F G H J K`: タッチパッド演奏
- `E`: FX ON / OFF
- `R`: REC / ARM / OVERDUB
- `U`: Undo
- `C`: Clear active deck
- `Space`: Play / Stop
- `Z`: 前の音色
- `X`: 次の音色
- `Q`: オクターブ下げ
- `W`: オクターブ上げ

---

## 21. ゲームパッド操作

ゲームパッドにも対応しています。

### 主な割り当て
- `R`: REC
- `START + L`: Play / Stop
- `SELECT + L / R`: デッキ切り替え
- `SELECT + Y`: FX切り替え
- `SELECT + X`: シーケンス2倍
- `SELECT + A`: Undo
- `SELECT + B`: Clear active deck
- `L + 方向キー`: コードパッド
- `A / B / X / Y`: タッチパッド演奏
- `START + 方向キー`: 音色切り替えやオクターブ調整

### ゲームパッド対応の利点
- ライブ演奏に向いている
- モバイル環境でも扱いやすい
- アーケード風の演奏感が出せる

---

## 22. モバイル対応

タッチ操作前提で作られているので、スマホでも使えます。

### 特徴
- ピンチズームを抑制
- 大きめのボタン
- タッチ操作に最適化
- iPhone対応
- 一部ゲームパッドも利用可能

### ブラウザ注意
Instagram内ブラウザなどではファイル保存に制限があることがあります。  
Safari が比較的安定しています。

---

## 23. 画面表現

見た目はレトロゲーム機風です。

### 表現要素
- LEDインジケータ
- スキャンライン風の表示
- 発光ボタン
- パーティクル効果
- 低解像度風のUI

### 目的
音楽ツールというより、**演奏できる楽器**として感じられる見た目を目指しています。

---

## 24. パフォーマンス向け設計

このアプリは、単なる音楽再生ではなく、即興演奏向けに設計されています。

### 向いている使い方
- ライブ演奏
- ループベースの即興
- コード進行の作成
- レトロゲーム風の音楽制作
- モバイルでのジャムセッション
`
