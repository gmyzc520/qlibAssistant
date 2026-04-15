# params 
 {'predict_dates': [{'start': '2026-04-14', 'end': '2026-04-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260415_16 440837505151842195 (Recorders: 2/5)

	Recorder: f21e092ba5964abcb747d7c98f81355a

		Model: {'id': 'f21e092ba5964abcb747d7c98f81355a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.035, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.214', 'weight': '0.058'}

	Recorder: 856001d9fff24fc8a1acf262c9cded09

		Model: {'id': '856001d9fff24fc8a1acf262c9cded09', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.403, 'Rank IC': 0.052, 'Rank ICIR': 0.373}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.373', 'weight': '0.100'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260415_16 578292478678783639 (Recorders: 2/5)

	Recorder: 9c41d76e84c34a37a18e829421e336e4

		Model: {'id': '9c41d76e84c34a37a18e829421e336e4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.251, 'Rank IC': 0.035, 'Rank ICIR': 0.337}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.337', 'weight': '0.091'}

	Recorder: ee56b5cab5ac4451aca713a98e6e9c22

		Model: {'id': 'ee56b5cab5ac4451aca713a98e6e9c22', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.28, 'Rank IC': 0.035, 'Rank ICIR': 0.219}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.219', 'weight': '0.059'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260415_14 191371796555465021 (Recorders: 4/5)

	Recorder: bef6a46ea2414dc8b3a1a3564bc27b50

		Model: {'id': 'bef6a46ea2414dc8b3a1a3564bc27b50', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.024, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-04-15', '2025-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.139', 'weight': '0.037'}

	Recorder: 98a584bc0c174ceb942f9baaa7c219d8

		Model: {'id': '98a584bc0c174ceb942f9baaa7c219d8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.106, 'Rank IC': 0.052, 'Rank ICIR': 0.304}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.304', 'weight': '0.082'}

	Recorder: 96981671955c44d7a312a59c10fd4d62

		Model: {'id': '96981671955c44d7a312a59c10fd4d62', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.16, 'Rank IC': 0.023, 'Rank ICIR': 0.193}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.193', 'weight': '0.052'}

	Recorder: 872bedca746349968c6324424499db34

		Model: {'id': '872bedca746349968c6324424499db34', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.261, 'Rank IC': 0.033, 'Rank ICIR': 0.172}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.172', 'weight': '0.046'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260415_14 812065256375710443 (Recorders: 4/5)

	Recorder: a3a4c775db0a4e3da863c797c7b7c5c1

		Model: {'id': 'a3a4c775db0a4e3da863c797c7b7c5c1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.052, 'Rank IC': 0.018, 'Rank ICIR': 0.164}, 'data_train_vec': ['2021-04-15', '2025-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.164', 'weight': '0.044'}

	Recorder: 27eadaeaf32a4536826ba8d0ec98788d

		Model: {'id': '27eadaeaf32a4536826ba8d0ec98788d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.061, 'Rank IC': 0.036, 'Rank ICIR': 0.307}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.307', 'weight': '0.083'}

	Recorder: 7e3bcf64d57741c091a38f4fe9b56cf7

		Model: {'id': '7e3bcf64d57741c091a38f4fe9b56cf7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.015, 'Rank ICIR': 0.128}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.128', 'weight': '0.034'}

	Recorder: 855dec5443a54a8aa73621b673fbf0c6

		Model: {'id': '855dec5443a54a8aa73621b673fbf0c6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.479, 'Rank IC': 0.059, 'Rank ICIR': 0.362}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.362', 'weight': '0.098'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260415_14 433885796298666019 (Recorders: 3/5)

	Recorder: 8f5984473d3a4f80a46da1fa2f4bb7b8

		Model: {'id': '8f5984473d3a4f80a46da1fa2f4bb7b8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.096, 'Rank IC': 0.044, 'Rank ICIR': 0.272}, 'data_train_vec': ['2023-04-15', '2025-07-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.272', 'weight': '0.073'}

	Recorder: f4124ca71b4344a7a0310a6d521fbf5d

		Model: {'id': 'f4124ca71b4344a7a0310a6d521fbf5d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.045, 'Rank IC': 0.038, 'Rank ICIR': 0.338}, 'data_train_vec': ['2024-04-15', '2025-10-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.338', 'weight': '0.091'}

	Recorder: 3b7c63afd2a746289cccfdca46568685

		Model: {'id': '3b7c63afd2a746289cccfdca46568685', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.297, 'Rank IC': 0.028, 'Rank ICIR': 0.19}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15'], 'rank_icir': '0.190', 'weight': '0.051'}
