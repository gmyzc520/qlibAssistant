# params 
 {'predict_dates': [{'start': '2026-05-07', 'end': '2026-05-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260507_17 916538348529353985 (Recorders: 2/5)

	Recorder: c88e3d96f8a04bf7b037ef83850eaf8d

		Model: {'id': 'c88e3d96f8a04bf7b037ef83850eaf8d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.055, 'Rank IC': 0.024, 'Rank ICIR': 0.179}, 'data_train_vec': ['2024-05-07', '2025-11-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.179', 'weight': '0.107'}

	Recorder: d1d2ad993a8a44d491e15cace874d344

		Model: {'id': 'd1d2ad993a8a44d491e15cace874d344', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.438, 'Rank IC': 0.023, 'Rank ICIR': 0.183}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.183', 'weight': '0.110'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260507_17 846672952249110881 (Recorders: 2/5)

	Recorder: e7fe85afde34491a9519617f7e16358c

		Model: {'id': 'e7fe85afde34491a9519617f7e16358c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.239, 'Rank IC': 0.024, 'Rank ICIR': 0.199}, 'data_train_vec': ['2024-05-07', '2025-11-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.199', 'weight': '0.119'}

	Recorder: 1c711c198e1d44be819ade28b695e4dc

		Model: {'id': '1c711c198e1d44be819ade28b695e4dc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.084, 'ICIR': 0.662, 'Rank IC': 0.035, 'Rank ICIR': 0.335}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.335', 'weight': '0.200'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260507_14 711865475946645518 (Recorders: 2/5)

	Recorder: 874be068e86b43a88c5c3c1fe1e10e2a

		Model: {'id': '874be068e86b43a88c5c3c1fe1e10e2a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.045, 'Rank IC': 0.033, 'Rank ICIR': 0.198}, 'data_train_vec': ['2023-05-07', '2025-08-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.198', 'weight': '0.118'}

	Recorder: a6bc6acf9f23458193dc75452f77878d

		Model: {'id': 'a6bc6acf9f23458193dc75452f77878d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.424, 'Rank IC': 0.019, 'Rank ICIR': 0.151}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.151', 'weight': '0.090'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260507_14 265020873879650391 (Recorders: 2/5)

	Recorder: ca3b2ec7251b4739b10892359734be0a

		Model: {'id': 'ca3b2ec7251b4739b10892359734be0a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.052, 'Rank IC': 0.017, 'Rank ICIR': 0.156}, 'data_train_vec': ['2024-05-07', '2025-11-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.156', 'weight': '0.093'}

	Recorder: 976fbee5cc694160b4c9d87ab3118cd3

		Model: {'id': '976fbee5cc694160b4c9d87ab3118cd3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.547, 'Rank IC': 0.021, 'Rank ICIR': 0.189}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.189', 'weight': '0.113'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260507_14 327647087179682638 (Recorders: 1/5)

	Recorder: 626727f1df6042ab9a753acf04589c5e

		Model: {'id': '626727f1df6042ab9a753acf04589c5e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.401, 'Rank IC': 0.008, 'Rank ICIR': 0.081}, 'data_train_vec': ['2025-05-07', '2026-02-06'], 'train_time_vec': ['2026-05-07', '2026-05-07'], 'rank_icir': '0.081', 'weight': '0.048'}
