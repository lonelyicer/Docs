# <img class="dark-only" src="/eye_tracking_settings_icon.png" alt="Eye Tracking Settings" style="width: 32px; height: 32px; vertical-align: -4px; display: inline;"/> <img class="light-only" src="/eye_tracking_settings_icon_light_mode.png" alt="Eye Tracking Settings" style="width: 32px; height: 32px; vertical-align: -4px; display: inline;"/> 眼球追跡設定
<ruby>眼球追跡設定<rt>Eye Tracking Settings</rt></ruby> はユーザーが眼球追跡の設定を調整しやすくするためのコンポーネントです。以下のパラメータを調整できます：

**Eye Weight**（眼球の重み係数）と **Reset Weight**（リセットの重み係数）。

![Eye Tracking Settings](/eye_tracking_settings.png)
## パラメータ
**Eye Weight** は眼球追跡用の `EyeClosed` シェイプキーの強さを表します。カスタマイズした目がデフォルトより小さい場合は、値を減らしてください。

**Reset Weight** は、目が完全に閉じたときにカスタマイズした目の形をデフォルトに戻す強さを表します。目が開いているときはリセットの重み係数は0で、目が閉じたときに設定した目標値に徐々にブレンドされます。

これらの設定は眼球追跡の体験を微調整し、さまざまな目の形や大きさにシームレスに対応できるようにします。

## Preview ボタン
`Preview` ボタンをクリックすると、調整した内容のプレビューを表示できます。ボタンをクリックするとプレビューモードに入り、パラメータスライダーを調整することでもプレビューモードが有効になります。プレビューモードを終了して結果を保存するには、再度ボタンをクリックしてください。コンポーネントがフォーカスを失うと、プレビューモードは自動的に終了して変更が保存されますが、すべてが正しく保存されるようにするためにボタンをクリックすることをお勧めします。

![Preview](/eye_tracking_settings_preview.png)

## クリエイター設定
**Creator Settings** は、ユーザーが変更しないようにすべき領域であり、変更すると問題が発生する可能性があります。この部分はフェイストラッキングのクリエイター専用に設計されています。